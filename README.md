# Cellbio Project

This project analyzes single-cell RNA-seq data to classify cells and patients based on disease severity using machine learning techniques.

## Contents

- `.h5` files — scRNA-seq data for each sample
- `Finalcoding.ipynb` — Main analysis notebook
- `cell_level_predictions.csv` — SVM predictions at the cell level
- `patient_level_predictions.csv` — Aggregated predictions at the patient level

## Note on Missing Files

⚠️ Three large files (`pca_train.csv`, `pca_test.csv`, and `GSM4339771_C143_filtered_feature_bc_matrix.h5`) were **intentionally excluded** from this repository due to GitHub’s file size restrictions.

Please contact the author if you need access to these files for replication purposes.

## How to Run

1. Clone the repository
2. Install dependencies (Python, scikit-learn, etc.)
3. Open `Finalcoding.ipynb` and run the analysis

