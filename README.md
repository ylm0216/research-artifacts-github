# Research Artifacts

This repository contains the lightweight, shareable data and configuration package for the Chinese painting artistic-conception evaluation project. The current version is limited to curated evaluation data, task definitions, model configurations, experiment protocol metadata, and public-source records.

## Repository Contents

- `data/curated/`: curated evaluation data, including the CII-Bench painting subset, balanced TCC-Bench data, and the L1-L4 artistic-conception evaluation files.
- `data/curated/ideation-eval/`: task items, paired probes, L4 reference texts, expert annotation sheets, scoring templates, and field schemas.
- `data/metadata/`: dataset catalog and provenance information.
- `data/references/painting-form/`: PaintingForm source records, dataset identifiers, and original download pointers. The complete image archive is not included.
- `configs/experiments/`: experiment protocol and evaluation-condition configuration.
- `configs/models/`: local model settings, model registry, and service configuration templates.

## Data Sources

The curated files are organized for direct inspection and reuse in the evaluation workflow. Dataset identifiers, source URLs, and related provenance records are provided under `data/metadata/` and `data/references/painting-form/`.

## Usage

The task schemas, evaluation items, paired probes, reference texts, scoring templates, experiment protocol, and model configuration files should be used together to maintain consistent dataset and evaluation definitions.
