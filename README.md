# ECP-RCG-ED: experimental inputs and final results

This repository is the public, non-enterprise data package supporting the ECP-RCG-ED study.

## Included

- `experiment_inputs/`: non-enterprise benchmark, generated structural, CVaR, and equivalence-degree instances used in the reported computational experiments;
- `final_results/`: final summary tables, audit/hash records, and compact CSV exports derived from completed experiment records;
- `reports/`: experiment reports needed to interpret the result tables;
- `DATA_MANIFEST.csv`: SHA-256 checksums for every released file.

The compact exports contain 54 ECP-RCG-ED ablation records, 153 baseline-comparison records, 48 CVaR-ablation records, and 4 equivalence-degree records. They retain outcome and timing fields only; per-iteration traces and route-level operational output are not included.

## Excluded

This repository does **not** contain enterprise operational data, identifying information, original corporate records, raw solver logs, stdout/stderr captures, per-iteration traces, route-level output, or internal working files. Those materials are outside the public release scope.

## Reuse and verification

Use `DATA_MANIFEST.csv` to verify file integrity. The public data package is released under [CC BY 4.0](LICENSE.md). Please cite the associated study and this versioned repository tag (`v1.0.0`) when reusing the material.

## Release citation

The public package contains non-enterprise experimental inputs, final result tables, and compact source-data exports. Enterprise operational data and raw route-level records are not included because of commercial confidentiality.
