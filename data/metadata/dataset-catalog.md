# Dataset catalog

| Dataset | Role in paper | Local location | Status |
|---|---|---|---|
| CII-Bench | Cross-benchmark Chinese image implication comparison | `data/source/cii-bench-data` | Development (35) and test (765) Parquet files ready |
| CII-Bench painting subset | Traditional painting subset for comparison | `data/curated/cii-bench-painting-subset.parquet` | Curated subset ready, 125 records; image metadata retained for review |
| TCC-Bench | Traditional Chinese culture VQA comparison | `data/source/tcc-bench/raw` | 1,015 questions and all 770 referenced image filenames present; one image reconstructed from the cited Baidu source page and documented in `dataset-record.json` |
| PaintingForm | L4 reference corpus | `data/references/painting-form` | 224,850 training records plus Gemini/GPT test sets (5,000 each) ready; 10.05 GB image archive needs to be re-fetched because the prior transfer did not persist |
| CArtBench | Chinese artwork comparison | `data/source/cartbench` | Upstream repository currently contains a README only; arXiv paper source and release-monitor note stored, no benchmark files publicly exposed |
| Traditional painting theory | Theory-derived reference text | `data/references/theory` | Dimension schema and three Wikisource source records/indexes prepared; direct raw endpoint returned access-check responses, so scholarly text extraction remains a source-acquisition task |

## Verification scope

The catalog is checked against the dataset names, roles, and links in `其他/大纲.docx`. Files are kept under source, curated, references, and metadata so experiments can point to stable paths without modifying raw material.
