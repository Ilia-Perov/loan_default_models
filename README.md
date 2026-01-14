# Loan Default Prediction: Model Validation Project

## Overview
This project focuses on building and validating machine learning models for loan default prediction.
The main goal is not only to train models, but to perform proper model validation, interpretability analysis,
and assessment of potential model risks, following practices commonly used in banking and fintech.

## Dataset
The project uses an open loan default dataset containing demographic, financial, and loan-related features.
- ~255k loan records
- Numerical and categorical features
- Binary target variable: Default (0 — non-default, 1 — default)

## Project Structure
```
loan_default_validation/
├── data/
│   ├── raw/
├── notebooks/
│   └── main.ipynb
├── outputs/
├── report/
│   └── models_report.md
└── README.md
```

## Workflow
1. Exploratory Data Analysis (EDA) and data quality assessment
2. Data preprocessing and feature encoding
3. Model training (Logistic Regression as baseline, Gradient Boosting as ML model)

## Models
- Logistic Regression (baseline, interpretable)
- Gradient Boosting (higher predictive performance)

## Evaluation Metrics
- ROC AUC
- Gini coefficient
- Confusion matrix
- Calibration curves
- KS coefficient

## Technologies
- Python (pandas, numpy, scikit-learn)
- LightGBM / Gradient Boosting
- PySpark
- Jupyter Notebook
