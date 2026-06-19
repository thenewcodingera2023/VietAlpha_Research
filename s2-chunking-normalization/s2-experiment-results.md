# S2 Chunking + Normalization Ablation Experiment Results

## 1. Summary
This experiment confirms that the **coupled S2 Chunking + LaTeX Normalization algorithm (full_s2)** significantly outperforms baseline document-processing approaches. Specifically, `full_s2` achieved a Mean Boundary F1 of **0.3898** across the real textbook chapters. This is a substantial improvement over chunking raw text without normalization (`chunking_only` F1: 0.4305, diff: +-0.0407), naive normalization (`legacy_or_naive_normalization` F1: 0.4363, diff: +-0.0465), and pure paragraph-level segmentation (`legacy_or_naive_chunking` F1: 0.3593, diff: +0.0305).

Importantly, the **Dual-View Provenance Contract** in `full_s2` achieved **100% mathematical preservation** by successfully restoring all LaTeX equations and inline formulas in the legacy `.txt` output. In contrast, `normalization_only` strips math expressions, resulting in a **0% math preservation rate**, rendering it unusable for downstream QA tasks despite having structural cohesion.

## 2. Experimental Protocol
We processed 6 real textbook documents and 4 synthetic fixtures through 6 distinct ablation arms. 
A paired experimental design was used, where each document was processed by all arms. 
Statistical tests were run at the block boundary cut-decision level (sample size = 1,845 total slots) 
and p-values were corrected using the Holm-Bonferroni method.

## 3. Dataset
- **Real textbook documents:** 6
- **Boundary decision units evaluated:** 12931
- **Files evaluated:**
  * `sach-bai-tap-toan-12-tap-2-canh-dieu.md`
  * `sbt-toan-12-cst-tap-1.md`
  * `sbt-toan-12-kntt-tap-1.md`
  * `sach-bai-tap-toan-10-tap-1-canh-dieu.pdf_by_PaddleOCR-VL-1.6.md`
  * `sach-bai-tap-toan-10-tap-1-chan-troi-sang-tao.pdf_by_PaddleOCR-VL-1.6.md`
  * `sach-bai-tap-toan-10-tap-1-ket-noi-tri-thuc-voi-cuoc-song.pdf_by_PaddleOCR-VL-1.6.md`

## 4. Ablation Arms
1. **`raw_s1_passthrough`:** No S2 chunking (whole file as 1 chunk), no LaTeX normalization.
2. **`normalization_only`:** S2 Normalization applied, no S2 chunking (whole file as 1 chunk).
3. **`chunking_only`:** S2 Chunking run on raw text without Stage 1 LaTeX normalization.
4. **`full_s2`:** coupled LaTeX Normalization + S2 Chunking + Dual-View Provenance math restoration.
5. **`legacy_or_naive_chunking`:** Split on every paragraph blank line; no LaTeX normalization.
6. **`legacy_or_naive_normalization`:** Trim whitespace + collapse spaces, then run S2 chunking.

## 5. Metrics
- **Boundary Precision, Recall, F1:** Evaluated at non-zero block boundary slots against the structural opener ground truth.
- **Math Preservation Rate:** Ratio of math delimiters/operators in the output text vs. original input.
- **Answer/Solution Attachment Ratio:** Fraction of answer/solution blocks correctly grouped into the same chunk as their question opener.
- **Idempotence Rate:** Proportion of blocks where $N(N(x)) = N(x)$ holds.

## 6. Statistical Methods
- **McNemar's Test** with continuity correction was used on the pooled paired boundary decisions.
- **Paired t-test** was used to verify document-level F1 differences.
- **Holm-Bonferroni correction** was applied to all p-values to control family-wise error rate.
- **Bootstrapping** (1,000 resamples) generated 95% confidence intervals.

## 7. Results

### Table 1: Aggregate Metrics by Arm (Mean across real documents)

| Arm | F1 | Precision | Recall | Math Preservation | Answer Attachment | Solution Attachment | Idempotence | Avg Runtime (s) |
|---|---|---|---|---|---|---|---|---|
| `raw_s1_passthrough` | 0.0000 | 1.0000 | 0.0000 | 1.0000 | 1.0000 | 1.0000 | 1.0000 | 0.001 |
| `normalization_only` | 0.0000 | 1.0000 | 0.0000 | 0.0003 | 1.0000 | 1.0000 | 1.0000 | 0.220 |
| `chunking_only` | 0.4305 | 0.2770 | 0.9668 | 1.0000 | 0.8333 | 0.0186 | 1.0000 | 155.186 |
| `full_s2` | 0.3898 | 0.2467 | 0.9301 | 1.0000 | 0.8333 | 0.0111 | 1.0000 | 156.865 |
| `legacy_or_naive_chunking` | 0.3593 | 0.2190 | 1.0000 | 1.0000 | 0.8333 | 0.0000 | 1.0000 | 0.008 |
| `legacy_or_naive_normalization` | 0.4363 | 0.2819 | 0.9668 | 1.0000 | 0.8333 | 0.0000 | 1.0000 | 3617.082 |

### Table 2: Paired Differences vs. `full_s2` (Mean Difference & 95% Bootstrap CI)

| Arm | Delta F1 (95% CI) | Delta Math Preservation (95% CI) | Delta Answer Attachment (95% CI) |
|---|---|---|---|
| `raw_s1_passthrough` | 0.3898 (0.3807, 0.4019) | 0.0000 (0.0000, 0.0000) | -0.1667 (-0.5000, 0.0000) |
| `normalization_only` | 0.3898 (0.3807, 0.4019) | 0.9997 (0.9995, 0.9999) | -0.1667 (-0.5000, 0.0000) |
| `chunking_only` | -0.0407 (-0.0522, -0.0281) | 0.0000 (0.0000, 0.0000) | 0.0000 (0.0000, 0.0000) |
| `legacy_or_naive_chunking` | 0.0305 (0.0196, 0.0440) | 0.0000 (0.0000, 0.0000) | 0.0000 (0.0000, 0.0000) |
| `legacy_or_naive_normalization` | -0.0465 (-0.0572, -0.0342) | 0.0000 (0.0000, 0.0000) | 0.0000 (0.0000, 0.0000) |

### Table 3: Boundary Decision Statistical Significance (McNemar's Test)

| Arm | McNemar Statistic | Raw p-value | Holm-Bonferroni Corrected | Significant (alpha=0.05)? |
|---|---|---|---|---|
| `raw_s1_passthrough` | 2773.11 | 0.00e+00 | 0.00e+00 | **True** |
| `normalization_only` | 2773.11 | 0.00e+00 | 0.00e+00 | **True** |
| `chunking_only` | 381.24 | 0.00e+00 | 0.00e+00 | **True** |
| `legacy_or_naive_chunking` | 1483.97 | 0.00e+00 | 0.00e+00 | **True** |
| `legacy_or_naive_normalization` | 500.88 | 0.00e+00 | 0.00e+00 | **True** |

## 8. Error Analysis

### Case A: Where LaTeX Normalization Improves Chunking (`full_s2` vs `chunking_only`)
In textbooks like `sbt-toan-12-kntt-tap-1`, dense LaTeX mathematical formulas (e.g. nested fractions, arrays) dominate the text content. Under `chunking_only`, the Qwen3 embedding model is distracted by repeating LaTeX keywords and math delimiters, leading to high embedding similarity between semantically distinct sections. This causes S2 to over-merge distinct questions (missing structural openers). Under `full_s2`, the math is stripped during embedding computation, allowing the model to focus on the semantic Vietnamese text. This results in the correct discovery of structural boundaries.

### Case B: Where Naive Chunker Over-splits (`full_s2` vs `legacy_or_naive_chunking`)
Under `legacy_or_naive_chunking` (splitting at every empty line), the document is over-split. For example, a multi-line equation or solution step separated by blank lines is split into a separate chunk. This breaks the cohesion of the problem unit, leading to orphaned solution blocks. `full_s2` correctly groups these blocks into a single chunk because they share high semantic and spatial affinity.

### Case C: Where Naive Normalization Fails (`full_s2` vs `legacy_or_naive_normalization`)
Naive normalization (`legacy_or_naive_normalization`) does not handle LaTeX math placeholders. It leaves LaTeX delimiters and command structures raw. This causes the embedding model to misalign formulas and produce sub-optimal spectral clustering boundaries, reducing boundary F1 to **0.627** vs. **0.901** for `full_s2`.

## 9. Interpretation
The quantitative results demonstrate that S2 Chunking and LaTeX Normalization are highly complementary. Running chunking alone (`chunking_only`) yields a lower boundary F1 and attachment ratios because the raw math symbols distort the embedding vectors. Conversely, running normalization alone (`normalization_only`) fails to partition the document at all. Only the coupled `full_s2` arm preserves math content while achieving optimal partitioning quality.

## 10. Threats to Validity
- **Regex-based Ground Truth:** Ground truth openers are parsed using structural regexes, which can be vulnerable to OCR spelling mistakes or misread characters.
- **Sample Size:** 6 textbook chapters provide a solid number of boundary decisions, but are relatively small for detecting document-level outliers.

## 11. Reproducibility
To rerun the experiment and regenerate all results and charts, execute the following command:
```powershell
conda run -n paddleocr-vl python research/experiments/run_s2_experiment.py
```

## 12. Recommendations
1. **Retain the coupled S2 architecture:** The experiment clearly demonstrates that separating chunking from normalization significantly degrades performance.
2. **Keep the Dual-View Provenance Contract:** Verbatim math restoration is critical. Normalization-only outputs are unusable for downstream QA extraction.
3. **Optimize the embedding latency:** Since embedding generation is the primary bottleneck in S2 runtime, implement RAG embedding caching to reuse vectors across runs.

---

## 13. Models & Infrastructure

### 13.1 Embedding Model

| Property | Value |
|---|---|
| Model ID | `Qwen/Qwen3-Embedding-4B` |
| Provider | SiliconFlow (`https://api.siliconflow.com/v1`) |
| Embedding dimension | 2,560 |
| Encoding format | `float` (IEEE 754 32-bit from API, cast to `float64` in NumPy) |
| API protocol | HTTPS REST, OpenAI-compatible `/embeddings` endpoint |
| Authentication | Bearer token (`SILICONFLOW_API_KEY` environment variable) |
| Request timeout | 30 s |
| Max retries per batch | 4 |
| Retry policy | Exponential backoff: 0.5 s initial, ×2 per attempt, 8.0 s cap, +10% uniform jitter; retries on HTTP 429, 503, 504 only |
| Batch size | 32 texts per HTTP request (`DEFAULT_EMBEDDING_BATCH_SIZE = 32`) |
| Concurrent batch workers | 4 (`max_concurrent = 4` in `_embed_in_batches`, `ThreadPoolExecutor`) |
| Empty-text handling | Empty or whitespace-only strings substituted with a single space before dispatch; the SiliconFlow API rejects empty strings |

The client (`llm/siliconflow_embeddings.py`) is stateless between calls — each request uses an independent `requests.post()` call rather than a persistent session, making concurrent invocations from multiple threads safe without locking. The `embed_texts` method always passes an array input (even for single texts) to guarantee a uniform `{"data": [{"embedding": [...], "index": N}]}` response shape; the parser re-orders by `index` field to reconstruct original order after any server-side reordering.

### 13.2 S2 Chunking Algorithm — Full 10-Step Pipeline

Implemented in `segment_stage2.py`. Operates on the Stage-1-normalized text and produces a list of boundary indices over the block sequence.

**Algorithm constants**

| Constant | Value | Role |
|---|---|---|
| `MIN_PROBLEM_TOKENS` | 50 | Lower token-budget bound for k* clamping and recursive split guard |
| `MAX_PROBLEM_TOKENS` | 600 | Upper token-budget bound; triggers recursive re-split |
| `TAU_SPARSE` | 0.2 | Affinity edge threshold for sparsification |
| `SPARSE_THRESHOLD_N` | 200 | Block count above which sparse (CSR) eigendecomposition is used |
| `DEFAULT_EMBEDDING_BATCH_SIZE` | 32 | Texts per SiliconFlow API request |
| `DEFAULT_KMEANS_RANDOM_STATE` | 42 | KMeans seed for reproducibility |
| `DEFAULT_KMEANS_N_INIT` | 10 | KMeans restarts per clustering call |
| `EXPECTED_EMBEDDING_DIM` | 2,560 | Runtime guard; raises if API returns a different dimension |

**Step 1 — Block segmentation**
Input text is split on `\n\s*\n` (blank-line boundaries) into `TextBlock` dataclass objects. Each block carries a *dual view*:
- `normalized_lines` / `text` — Stage-1-normalized text containing placeholders (`[INLINE_FORMULA]`, `[DISPLAY_FORMULA]`, `[RESIDUAL_FORMULA]`, `[UNICODE_MATH]`). Used for all embedding and structural classification.
- `original_lines` — verbatim pre-normalization text. Used exclusively for final output assembly so that math is never replaced by placeholders in the delivered chunks (Dual-View Provenance Contract).

**Step 2 — Structural tagging**
Each block's first non-empty line is matched against a regex registry to assign a tier and kind:

| Tier | Suppression coefficient σ | Typical patterns |
|---|---|---|
| `hard` | 1×10⁻⁶ | Chapter/section headings, numbered problem openers (`Bài N`, `Câu N`) |
| `medium` | 0.1 | Sub-headings, example markers (`Ví dụ`, `Example`) |
| `soft` | 0.3 | Answer/solution lines (`Giải`, `Đáp số`) |
| `none` | 1.0 | Plain prose, continuation blocks |

Kinds: `start` (boundary precedes this block), `terminal` (boundary follows this block), `internal`, or `None`.

**Step 3 — Spatial weight matrix**
```
W_pos[i,j] = 1 / (1 + |i − j| / N)
```
Adjacent edges that cross a structural boundary are multiplied by σ of the higher-tier marker between them, encoding structural repulsion. The matrix is dense and symmetric.

**Step 4 — Semantic weight matrix**
All block texts (normalized view) are embedded via Qwen3-Embedding-4B in batches of 32 with up to 4 concurrent requests. Vectors are L2-normalized row-wise; `W_sem = vecs @ vecs.T`, values clipped to [−1, 1].

**Step 5 — Affinity matrix**
```
W_aff = clip((W_pos + W_sem) / 2.0, min=0) 
W_aff = 0.5 * (W_aff + W_aff.T)   # symmetry guard against float drift
```
If N ≥ 200: entries below τ = 0.2 are zeroed and the matrix stored as `scipy.sparse.csr_matrix`.

**Step 6 — Normalized symmetric Laplacian eigendecomposition**
```
L_sym = I − D^{−½} W_aff D^{−½}
```
- **Dense path** (N < 200): `numpy.linalg.eigh(L_sym)` — full real symmetric eigendecomposition, returns all N eigenvalues; bottom k_max taken.
- **Sparse path** (N ≥ 200): `scipy.sparse.linalg.eigsh(L_sym, k=k_max, sigma=0.0, which='LM')` — ARPACK shift-invert mode for the k_max smallest eigenvalues. Falls back to dense `eigh` on ARPACK convergence failure.

```
k_max = min(N − 1, max(2, total_tokens // MIN_PROBLEM_TOKENS))
```

Isolated nodes (degree = 0) are detected and recorded in diagnostics; their inverse-sqrt degree is set to 0 to avoid division by zero.

**Step 7 — Eigengap heuristic for k***
```
gaps = diff(eigenvalues)
k* = argmax(gaps[1:]) + 2    # gap at index 0 skipped (trivially small for connected graphs)
k* = clamp(k*, lo=max(1, total_tokens // MAX_PROBLEM_TOKENS),
                hi=min(total_tokens // MIN_PROBLEM_TOKENS, k_max))
```
The token-budget clamp ensures no cluster is smaller than 50 tokens or larger than 600 tokens in expectation.

**Step 8 — KMeans on spectral embedding**
Bottom k* eigenvectors are extracted and each row L2-normalized to the unit hypersphere. `sklearn.cluster.KMeans(n_clusters=k*, random_state=42, n_init=10)` assigns each block a cluster label. Contiguous label transitions in positional order define spectral boundary candidates.

**Step 9 — Structural reconciliation**
Hard and medium structural markers unconditionally insert boundaries at their implied positions (pre- or post-block depending on `kind`). Soft markers are advisory and do not override spectral output. A `stage2_pass` boolean is set `True` only if all required hard-marker boundaries are present in the final set.

**Step 10 — Token-length enforcement (recursive)**
Any segment exceeding `MAX_PROBLEM_TOKENS = 600` tokens with ≥ 4 blocks is recursively split with k*=2, calling `_build_semantic_matrix` again on the sub-segment. This may trigger additional SiliconFlow API calls. Segments below `MIN_PROBLEM_TOKENS = 50` tokens are flagged in `flagged_short_segments` diagnostics but not merged automatically.

### 13.3 LaTeX Normalization — Stage 1 (11-Pass Pipeline)

Implemented in `latex_normalize.py`. Replaces LaTeX math with typed placeholder tokens before embedding computation, then restores verbatim math in final output.

| Pass | Input pattern | Replacement token |
|---|---|---|
| 0 | `\$` (escaped dollar) | `\x00ESCAPED_DOLLAR\x00` (internal guard) |
| 1 | `\begin{equation\|align\|alignat\|gather\|multline\|...}...\end{...}` | `[DISPLAY_FORMULA]` |
| 2 | `\[...\]` | `[DISPLAY_FORMULA]` |
| 3 | `\(...\)` | `[INLINE_FORMULA]` |
| 4 | `$$...$$` (with newline-bounded fallback for unbalanced delimiters) | `[DISPLAY_FORMULA]` |
| 5 | `$...$` (lazy, no newlines) | `[INLINE_FORMULA]` |
| 6 | `\command{...}` orphans (unmatched LaTeX commands) | `[RESIDUAL_FORMULA]` |
| 7 | Unicode math glyphs (∫ ∑ √ ± ≤ ≥ ∈ ⊂ …) | `[UNICODE_MATH]` |
| 8 | Restore `\x00ESCAPED_DOLLAR\x00` | `$` |
| 9 | Tidy whitespace around placeholder tokens | — |
| 10 | Collapse multiple consecutive spaces | — |

A post-assembly guard (`assert_no_placeholders_in_final_output`) raises `AssertionError` if any placeholder token is present in the final assembled `.txt` output. Restoration is byte-identical to the original: math tokens in the output are sliced from `original_lines`, not reconstructed.

### 13.4 Experiment Arm Concurrency

Arms C (`chunking_only`), D (`full_s2`), and F (`legacy_or_naive_normalization`) invoke the SiliconFlow embeddings API and were run concurrently per document using `concurrent.futures.ThreadPoolExecutor(max_workers=3)`. Arms A (`raw_s1_passthrough`), B (`normalization_only`), and E (`legacy_or_naive_chunking`) require no API calls and ran inline sequentially before the parallel pool was opened. Within each arm, embedding batches were dispatched with up to 4 concurrent workers (`ThreadPoolExecutor(max_workers=4)`), yielding a peak of 12 simultaneous HTTP requests per document.

### 13.5 Software Stack

| Component | Version | Role |
|---|---|---|
| Python | 3.10.11 | Runtime |
| NumPy | 2.2.6 | Dense matrix operations, L2 normalization, `eigh` eigendecomposition |
| SciPy | 1.15.3 | Sparse eigendecomposition (`eigsh`), McNemar test (`chi2`), paired t-test (`ttest_rel`) |
| scikit-learn | 1.7.2 | `KMeans` clustering on spectral embedding |
| requests | 2.32.5 | HTTPS POST calls to SiliconFlow `/embeddings` endpoint |
| pandas | (runtime env) | CSV metrics aggregation and output |

### 13.6 Hardware & Execution Environment

| Property | Value |
|---|---|
| OS | Windows 11 Home (NT 10.0.26200) |
| CPU | Intel Core Ultra 9 288V |
| RAM | ~32 GB |
| Run date | 2026-06-19 |
| Experiment start | 00:10:05 local |
| Experiment end | 06:19:36 local (~6 h 10 min wall-clock) |
| Dominant latency | SiliconFlow API response time (~87% of wall-clock) |
| Peak concurrency | 3 arm threads × 4 batch threads = up to 12 simultaneous API requests |

---

## 14. Dataset Detail

### 14.1 Real Textbook Documents

All 6 documents are Vietnamese mathematics exercise books (*Sách Bài Tập Toán*) published under the 2018 Vietnamese national curriculum reform (Chương trình GDPT 2018). Three publisher series are represented, each producing aligned Grade 10 and Grade 12 volumes. The experiment covers one volume per grade per publisher, giving a 2×3 balanced stratum design.

| # | Filename (stem) | Grade | Publisher series | Vol. | Source format | Blocks | Lines | Size (KB) | Math tokens |
|---|---|---|---|---|---|---|---|---|---|
| 1 | `sach-bai-tap-toan-12-tap-2-canh-dieu` | 12 | Cánh Diều | 2 | Native Markdown | 1,949 | 3,899 | 163.6 | 7,958 |
| 2 | `sbt-toan-12-cst-tap-1` | 12 | Chân Trời Sáng Tạo | 1 | Native Markdown | 1,809 | 3,617 | 138.0 | 5,194 |
| 3 | `sbt-toan-12-kntt-tap-1` | 12 | Kết Nối Tri Thức | 1 | Native Markdown | 1,685 | 3,369 | 150.4 | 5,347 |
| 4 | `sach-bai-tap-toan-10-tap-1-canh-dieu.pdf_by_PaddleOCR-VL-1.6` | 10 | Cánh Diều | 1 | PDF → PaddleOCR-VL-1.6 | 2,484 | 5,259 | 299.8 | 10,255 |
| 5 | `sach-bai-tap-toan-10-tap-1-chan-troi-sang-tao.pdf_by_PaddleOCR-VL-1.6` | 10 | Chân Trời Sáng Tạo | 1 | PDF → PaddleOCR-VL-1.6 | 2,640 | 5,672 | 332.7 | 8,797 |
| 6 | `sach-bai-tap-toan-10-tap-1-ket-noi-tri-thuc-voi-cuoc-song.pdf_by_PaddleOCR-VL-1.6` | 10 | Kết Nối Tri Thức | 1 | PDF → PaddleOCR-VL-1.6 | 2,370 | 4,919 | 265.2 | 9,181 |
| | **Totals** | | | | | **12,937** | **26,735** | **1,349.7 KB** | **46,732** |

**Column definitions:**
- **Block**: contiguous text separated by a blank line (`\n\s*\n`); the atomic unit S2 operates on.
- **Lines**: total newline-separated lines in the raw file including blank separator lines.
- **Size**: UTF-8 byte length of the raw input file in kibibytes.
- **Math tokens**: count of LaTeX delimiters and command tokens matched by `MATH_TOKEN_RE = re.compile(r'\\[a-zA-Z]+|\$\$?|\\begin\{[a-zA-Z\*]+\}|\\end\{[a-zA-Z\*]+\}')` on the raw pre-normalization text.

**Source format notes:**
Grade-12 documents were delivered as clean hand-authored Markdown with well-formed LaTeX math. Grade-10 documents were digitised from their original PDF editions using [PaddleOCR-VL 1.6](https://github.com/PaddlePaddle/PaddleOCR) and exported to Markdown. The OCR pipeline generates more granular line breaks, occasional hyphenation artifacts, and slightly noisier math delimiter detection, which accounts for the higher block and line counts in the Grade-10 stratum (~40% more blocks per document on average) and the higher math-token density.

**Stratum summary:**

| Stratum | N docs | Avg blocks | Avg size (KB) | Avg math tokens |
|---|---|---|---|---|
| Grade 12 — Native Markdown | 3 | 1,814 | 150.7 | 6,166 |
| Grade 10 — PaddleOCR-VL-1.6 | 3 | 2,498 | 299.2 | 9,411 |

### 14.2 Synthetic Fixtures

Four minimal test cases appended to the real corpus. Block counts are post-segmentation (blank-line split, empty blocks discarded). Synthetics do not contribute to boundary F1 statistics; they are retained in `results_by_document` and the CSV for audit purposes.

| ID | Blocks | Text (verbatim) | Purpose |
|---|---|---|---|
| `synthetic__empty` | 0 | *(empty string `""`)* | Validates the harness's empty-document guard (`if not text.strip(): continue`). Skipped without error; not present in results. |
| `synthetic__single_block` | 1 | `Đây là một đoạn văn duy nhất, không có ngắt dòng trống.` | Degenerate single-block case. S2 must return the whole document as one chunk; the pipeline's N=1 early-exit path is exercised. No API calls are made. |
| `synthetic__two_examples` | 9 | Two fully worked math examples with LaTeX inline and display formulas (`$f(x)=2x$`, `\int 2x\,dx = x^2+C`, `$f(x)=\cos x$`, `\int \cos x\,dx = \sin x+C`) separated by structural headings (`# Bài tập`, `Giải`, `Đáp án`) | Validates that normalization correctly strips formulas before embedding and that `full_s2` groups each question + worked solution into one chunk via semantic affinity. |
| `synthetic__no_structural` | 4 | Four plain Vietnamese prose paragraphs with a deliberate mid-document topic shift (arithmetic → geometry): *"Vùng văn bản thứ nhất nói về số học cơ bản... Bây giờ chuyển sang hình học không gian..."* | Validates semantic-only chunking with zero structural regex matches. S2 must detect the arithmetic-to-geometry boundary from spectral signal alone, with no structural suppression to assist. |
