# Data Preprocessing Pipeline

GTD preprocessing pipeline with distribution-aware imputation, reverse geocoding, and dual correlation-based feature reduction.

## Files
- `01_data_loading.py` — Load raw GTD Excel data
- `02_eda.py` — Exploratory data analysis
- `03_missing_value_imputation.py` — Skewness-based mean/median imputation
- `04_geocoding.py` — Reverse geocoding for missing locations
- `05_feature_engineering.py` — Feature selection (Pearson + NMI)
- `06_evaluation.py` — KL-divergence and VIF validation
- `config.py` — Configuration settings
- `run_pipeline.py` — Run the full pipeline
