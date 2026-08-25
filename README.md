# ECP-BP data release

This repository is the data-only replication package for the manuscript
Risk-Averse Fleet Coordination under Driving-Behavior-Based Safety Admission:
Formulation and Exact Solution Method.

ECP-BP denotes the Equivalence-Class Pricing-Based Branch-and-Price Algorithm,
the exact solution method developed and evaluated in the accompanying study.

## Included datasets

- `experiment_inputs/exact_benchmarks/`: 20 exact benchmark instances, comprising 14 formal benchmark instances and 6 additional CARE validation instances.
- `experiment_inputs/heldout_benchmarks/`: 12 held-out benchmark instances.
- `experiment_inputs/public_network_derived/`: 27 public-network-derived instances, including the 23 held-out instances used in the held-out summaries.
- `experiment_inputs/structural_factorial_instances/`: 108 factorial structural instances and 18 independent-seed replications, for 126 instances in total.
- `experiment_inputs/stochastic_cvar_instances/`: fixed 100-scenario model-ready instances used in the supplementary stochastic consistency check.
- `experiment_inputs/equivalence_profile_diagnostic/`: the four N=250 profile variants used in the supplementary diagnostic.
- `final_results/`: compact source-data exports, comparison tables, final audits, and supplementary diagnostic summaries supporting the non-confidential computational results reported in the manuscript and supplement.

## Excluded material

This release does not contain private operational records, identifying information, original corporate files, detailed enterprise inputs, raw solver logs, stdout or stderr captures, per-iteration traces, route-level operational output, software, or internal working files.

The model-ready instances in this repository are deidentified benchmark or generated inputs. Restricted calibration sources are not included.

## Paper-to-data map

See `SOURCE_DATA_MAP.csv` for the exact files supporting the main and supplementary computational tables and figures. Enterprise policy tables in the manuscript and supplement are outside the scope of this public data release.

## Verification and reuse

Use `DATA_MANIFEST.csv` to verify the size and SHA-256 digest of every released file. The data and documentation are released under CC BY 4.0; see `LICENSE.md`.

Please cite the associated manuscript and the versioned repository release when reusing these data.
