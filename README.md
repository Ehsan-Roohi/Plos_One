# Bibliometric comparison data

CSV data and robustness outputs for a cross-country publication, citation
impact, and international-collaboration analysis.

## File groups

- `fwci.csv`, `outputs.csv`, and `intl_collab.csv` — country-year panels;
  the `*_manual.csv` files retain manually exported comparison tables.
- `scival_merged_country_year.csv`, `scival_fwci_collab_gap_vs_iran.csv`, and
  `scival_period_summary.csv` — merged and summarized bibliometric panels.
- `scopus_pub_counts_MY_TH_ES_MX.csv` and
  `worldbank_predictors_extra_MY_TH_ES_MX.csv` — publication counts and
  country-year predictors.
- `expanded_*.csv` — synthetic-control/robustness outputs: donor weights,
  predictor balance, placebo RMSPE, leave-one-out, specification sensitivity,
  coverage, and the 2024 summary.
- `Field-Weighted_*.csv` and
  `Output_in_Top_10__Citation_Percentiles_(_)_vs_Publication_Year.csv` —
  field/year exports.

Files whose names end in ` (1).csv` are preserved upload duplicates.  Prefer
an otherwise identical filename without ` (1)` for new analysis, but verify
content hashes before treating two files as interchangeable.

## Reproducibility limits

The repository currently contains data products but no end-to-end analysis
script, data dictionary, source-retrieval log, citation metadata, or license.
A publication package should add the exact source/query date and definitions
for FWCI, output, international collaboration, treatment timing, donor pool,
predictors, and RMSPE calculations.  Do not infer provenance or redistribution
rights from a filename alone.

