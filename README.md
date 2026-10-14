# Research Artifacts

This repository contains the lightweight, shareable data and configuration package for the Chinese painting artistic-conception evaluation project. The current version is limited to curated evaluation data, task definitions, model configurations, experiment protocol metadata, and public-source records.

## Repository Contents

- `data/curated/`: curated evaluation data, including the CII-Bench painting subset, balanced TCC-Bench data, and the L1-L4 artistic-conception evaluation files.
- `data/curated/ideation-eval/`: task items, paired probes, L4 reference texts, expert annotation sheets, scoring templates, and field schemas.
- `data/metadata/`: dataset catalog and provenance information.
- `data/references/painting-form/`: PaintingForm source records, dataset identifiers, and original download pointers. The complete image archive is not included.
- `configs/experiments/`: experiment protocol and evaluation-condition configuration.
- `configs/models/`: local model settings, model registry, and service configuration templates.

## Scope and Exclusions

This repository does not currently include Python implementation code, model weights, raw model responses, experimental result figures, statistical result files, the complete PaintingForm image archive, or download caches. Large third-party data are referenced through their original source records and download links.

## Reproducibility

Reproduction should use the versioned data files, field schemas, experiment protocol, and model configuration files in this repository. Record the dataset version, model version, prompt condition, inference parameters, and runtime environment for each run. External datasets should be obtained from the original sources recorded under `data/references/painting-form/` and used according to their applicable licenses.