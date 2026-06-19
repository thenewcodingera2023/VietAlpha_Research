# S2 Chunking + Normalization Ablation Experiment Plan

This document defines the experimental protocol, methodology, and design for comparing document-processing quality with and without the implemented S2 Chunking + Normalization algorithms.

## 1. Research Question
Does the coupled S2 Chunking (spatial-semantic spectral clustering with structural prior suppression) and LaTeX Normalization algorithm improve document partitioning and downstream math content preservation compared to baseline approaches without these steps?

## 2. Hypotheses
* **Null Hypothesis ($H_0$):** The coupled S2 Chunking + Normalization algorithm does not improve partitioning quality (measured by chunk boundary F1 against a structural reference, answer/solution attachment ratios) or math preservation compared to baseline arms.
* **Alternative Hypothesis ($H_1$):** The S2 algorithm significantly improves document partitioning quality (higher boundary F1 and attachment ratios) and preserves mathematical content (zero placeholder leakage and 100% math token preservation) compared to baselines.

## 3. Unit of Analysis
* **Primary Unit:** The block boundary decision. For a document with $N$ blocks, there are $N-1$ potential boundary positions. At each position, the algorithm decides to split (1) or not split (0).
* **Secondary Unit:** The document level (for overall metrics like mean chunk length, runtime, and math preservation rates).

## 4. Dataset Selection Strategy
We select a diverse set of real textbooks from the pipeline's inputs (`sample/` and `input/` directories), covering multiple publishers (Cánh Diều, Chân Trời Sáng Tạo, Kết Nối Tri Thức) and grades. 

### Selected Dataset
1. `sample/sach-bai-tap-toan-12-tap-2-canh-dieu.md`
2. `input/2_12_textbooks_t1/sbt-toan-12-cst-tap-1.md`
3. `input/2_12_textbooks_t1/sbt-toan-12-kntt-tap-1.md`
4. `input/10_textbook_t1/sach-bai-tap-toan-10-tap-1-canh-dieu.pdf_by_PaddleOCR-VL-1.6.md`
5. `input/10_textbook_t1/sach-bai-tap-toan-10-tap-1-chan-troi-sang-tao.pdf_by_PaddleOCR-VL-1.6.md`
6. `input/10_textbook_t1/sach-bai-tap-toan-10-tap-1-ket-noi-tri-thuc-voi-cuoc-song.pdf_by_PaddleOCR-VL-1.6.md`

### Synthetic Fixtures
We also include the synthetic fixtures from `run_stage2_eval.py` to ensure baseline correctness on known edge cases:
1. `synthetic__empty`
2. `synthetic__single_block`
3. `synthetic__two_examples`
4. `synthetic__no_structural`

## 5. Inclusion/Exclusion Criteria
* **Inclusion:** Markdown files that represent complete textbooks or textbook chapters, containing both math formulas and Vietnamese prose.
* **Exclusion:** Files under `.ipynb_checkpoints/` or directory structures containing generated temporary runs.

## 6. Sampling Method
Since the available dataset is small (6 real textbook chapters and 4 synthetics), we use all eligible files without further sub-sampling. This represents the entire available evaluation split in the workspace.

## 7. Paired vs. Unpaired Comparison
The experiment is **paired**. Every selected document is processed under every ablation arm to ensure differences are attributable to the algorithm rather than dataset composition.

## 8. Ablation Arms
We define the following six arms:

1. **`raw_s1_passthrough` (Baseline A):**
   * Pre-S2 representation (no LaTeX normalization, no S2 chunking).
   * Treated as a single chunk containing the entire document.
2. **`normalization_only` (Baseline B):**
   * Apply Stage 1 LaTeX normalization to produce placeholders.
   * Do not apply S2 chunking (treated as a single chunk).
   * Math expressions are not restored (placeholders remain).
3. **`chunking_only` (Baseline C):**
   * Run S2 chunking directly on raw original text (normalization disabled).
   * The semantic weight matrix is computed on raw text embeddings.
   * Structural tagging and reconciliation run on raw text.
4. **`full_s2` (Arm D - Production):**
   * The current shipped pipeline: Stage 1 LaTeX normalization + Stage 2 graph-based segmenter + original-text legacy assembly.
5. **`legacy_or_naive_chunking` (Arm E):**
   * Naive chunker: splits the document purely by paragraph blank lines (each block is its own chunk).
   * No LaTeX normalization.
6. **`legacy_or_naive_normalization` (Arm F):**
   * Simple baseline normalizer: trim whitespace and collapse repeated spaces, but keep all LaTeX math intact.
   * Run S2 chunking on this naively normalized text.

## 9. Metrics

### Primary Metrics
1. **Chunk Boundary F1:** Harmonic mean of boundary precision and recall against the Ground Truth.
2. **Math Preservation Rate:** The ratio of LaTeX delimiters/operators in the output chunk text versus the input source text.
3. **Answer/Solution Attachment Ratio:** Proportion of `Đáp án`/`Giải` blocks correctly grouped into the same chunk as their preceding question opener.
4. **Normalization Idempotence Rate:** The proportion of blocks where $N(N(x)) = N(x)$.

### Ground Truth for Boundary Metrics
Ground Truth boundaries are defined as block indices that start with a valid structural opener according to `structural_patterns.py` (specifically: headings, example labels, exercise labels, exercise decimals, bold labels, and numbered items).

Let:
* $G$ be the set of Ground Truth boundary indices.
* $P$ be the set of predicted boundary indices.
* $TP = P \cap G$ (True Positives)
* $FP = P \setminus G$ (False Positives)
* $FN = G \setminus P$ (False Negatives)

$$\text{Precision} = \frac{|TP|}{|TP| + |FP|}$$
$$\text{Recall} = \frac{|TP|}{|TP| + |FN|}$$
$$\text{F1} = \frac{2 \cdot \text{Precision} \cdot \text{Recall}}{\text{Precision} + \text{Recall}}$$

### Secondary Metrics
* **Oversized Chunk Rate:** Fraction of chunks exceeding `max_tokens=600`.
* **Short Chunk Rate:** Fraction of chunks below `min_tokens=50`.
* **Orphan Chunk Rate:** Fraction of single-block chunks under `min_tokens`.
* **Runtime:** Time taken to segment the document (excluding API network latency when possible).

## 10. Statistical Tests
* **McNemar's Test:** Applied to paired boundary decisions (at each of the $N-1$ boundary slots) to test if the difference in accuracy (agreement with ground truth) between `full_s2` and baseline arms is statistically significant.
* **Paired t-Test / Wilcoxon Signed-Rank Test:** Applied to document-level F1 and attachment ratios across the selected documents.
* **Multiple Comparisons Correction:** We apply the **Holm-Bonferroni correction** to adjust p-values across the family of comparisons.

## 11. Bootstrap Confidence Intervals
We compute 95% confidence intervals using a **document-level paired bootstrap** with 1,000 resamples. Document-level resampling preserves the intra-document correlation between blocks.

## 12. Random Seed Policy
To ensure absolute determinism, we fix the random seeds:
* `SEED = 20260618` (used for KMeans `random_state` in S2 clustering).
* Numpy and random module seeds are pinned to `20260618`.

## 13. Reproducibility Policy
The experiment script will run fully non-interactively and emit:
* `research/s2-experiment-results.json`
* `research/s2-experiment-metrics.csv`
* `research/s2-experiment-results.md`

All commands to rerun the experiment will be listed under the Reproducibility section of the results.

## 14. Threats to Validity
* **Ground Truth Opener Proxy:** The ground truth relies on structural pattern classification. If the document has OCR errors that corrupt a structural opener, it won't be in the ground truth.
* **Mock vs. Real Embeddings:** We will run using the real `SiliconFlow` embedding API for semantic calculations to ensure the experiment matches production behavior.
* **Sample Size:** With 6 documents, the statistical power for document-level comparisons is limited. We mitigate this by evaluating at the block-boundary decision level ($> 1000$ decisions across all documents).

## 15. Execution Steps
1. Create `research/experiments/run_s2_experiment.py`.
2. Write unit tests / sanity checks for metric computations.
3. Load the selected documents, segment them into blocks, and run the 6 ablation arms.
4. Compute all boundary, normalization, and math preservation metrics.
5. Perform paired bootstrapping and statistical testing (McNemar's test, paired t-tests, Holm-Bonferroni).
6. Save the results to JSON, CSV, and generate the final report in Markdown.

## 16. Output Schema
The JSON output will strictly follow the schema requested in the user prompt.
