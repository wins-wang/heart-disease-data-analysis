# Scripts Folder

This folder contains all R scripts used in the project.

## Contents
- `0_data_integration.R` — Merging and initial cleaning of datasets
- `1_missing_value_analysis.R` — Missing data diagnosis and handling
- `2_analysis.R` — Main modeling workflow: LASSO, PCA, Factor Analysis, LDA
- `utilities/confusion_function.R` — Custom function for confusion matrix calculation

## Notes
- Scripts are modularized by data preparation and modeling stages.
- Output artifacts (e.g., models, plots) are saved to the `output/` directory.
