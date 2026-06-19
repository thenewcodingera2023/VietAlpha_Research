# S2 Chunking + Normalization — Ablation Experiment

This directory contains the results of an ablation study evaluating the coupled
**S2 Chunking (spatial–semantic spectral clustering) + LaTeX Normalization**
algorithm for partitioning Vietnamese mathematics textbooks, together with the
source textbook documents the experiment was run on.

## Contents

| File | Description |
|---|---|
| [`s2-experiment-plan.md`](s2-experiment-plan.md) | Experimental protocol: research question, hypotheses, ablation arms, metrics, and statistical methodology. |
| [`s2-experiment-results.md`](s2-experiment-results.md) | Full results report: aggregate metrics, paired differences, significance tests, error analysis, models/infrastructure, and dataset detail. |
| [`s2-experiment-results.json`](s2-experiment-results.json) | Machine-readable results (per-arm and per-document metrics, paired differences, CIs, statistical tests). |
| [`s2-experiment-metrics.csv`](s2-experiment-metrics.csv) | Flat per-arm metrics table. |
| [`s2-chunking-normalization.md`](s2-chunking-normalization.md) | Technical analysis of the S2 chunking + normalization algorithm and the Dual-View Provenance Contract. |
| [`sources/`](sources/) | The 6 real textbook documents used as experiment input. |

## Source textbooks

Six Vietnamese mathematics exercise books (*Sách Bài Tập Toán*) under the 2018
national curriculum (Chương trình GDPT 2018) — a 2×3 design across two grades
(10, 12) and three publisher series (Cánh Diều, Chân Trời Sáng Tạo, Kết Nối Tri
Thức). Grade-12 volumes are native Markdown; Grade-10 volumes were digitised
from PDF via PaddleOCR-VL 1.6.

| File | Grade | Publisher | Source format |
|---|---|---|---|
| `sources/sach-bai-tap-toan-12-tap-2-canh-dieu.md` | 12 | Cánh Diều | Native Markdown |
| `sources/sbt-toan-12-cst-tap-1.md` | 12 | Chân Trời Sáng Tạo | Native Markdown |
| `sources/sbt-toan-12-kntt-tap-1.md` | 12 | Kết Nối Tri Thức | Native Markdown |
| `sources/sach-bai-tap-toan-10-tap-1-canh-dieu.pdf_by_PaddleOCR-VL-1.6.md` | 10 | Cánh Diều | PDF → PaddleOCR-VL-1.6 |
| `sources/sach-bai-tap-toan-10-tap-1-chan-troi-sang-tao.pdf_by_PaddleOCR-VL-1.6.md` | 10 | Chân Trời Sáng Tạo | PDF → PaddleOCR-VL-1.6 |
| `sources/sach-bai-tap-toan-10-tap-1-ket-noi-tri-thuc-voi-cuoc-song.pdf_by_PaddleOCR-VL-1.6.md` | 10 | Kết Nối Tri Thức | PDF → PaddleOCR-VL-1.6 |

The `source_paths` field in `s2-experiment-results.json` records the original
in-pipeline paths of these documents for provenance; the same files are bundled
here under `sources/`.
