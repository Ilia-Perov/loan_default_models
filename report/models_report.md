1. **Objective**

The objective of this project is to assess the performance, stability, and interpretability

of machine learning models for loan default prediction.

Special attention is paid to model validation and identification of potential model risks.

2. **Data Description**

The dataset consists of approximately 255,000 loan records with numerical and categorical features,

including borrower demographics, credit characteristics, and loan parameters.

The target variable is binary:

- 0 — non-default

- 1 — default

3. **Data Quality and EDA Summary**

- No critical missing values or logical inconsistencies were identified

- Feature distributions are generally consistent with business expectations

- Key features (CreditScore, Income, DTI ratio) demonstrate meaningful relationships with default risk

4. **Models Overview**

Two models were developed and evaluated:

1. Logistic Regression

   - Used as a baseline model

   - Provides strong interpretability and regulatory transparency

2. Gradient Boosting Model

   - Provides higher predictive performance

   - Introduces increased complexity and model risk

**5. Model Performance**

Model performance was evaluated using ROC AUC, Gini coefficient, confusion matrices and KS coefficient.

The Gradient Boosting model outperformed Logistic Regression in terms of predictive power.
