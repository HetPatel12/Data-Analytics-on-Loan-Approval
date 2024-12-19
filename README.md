# Loan Approval Prediction

## Overview
A predictive model for loan approvals to assist lending institutions in making faster, data-driven decisions.

## Dataset
- **train.csv**: Labeled data with loan approval history.
- **test.csv**: Unlabeled data for predictions.
- **submission.csv**: Output file with predicted loan approvals.

## Methodology
1. **Data Preprocessing**:
   - Removed features with >20% missing values.
   - Handled outliers and engineered features (e.g., `Take Home Pay`, age metrics).

2. **Modeling**:
   - Used **XGBoost** for its efficiency with structured data.
   - Tuned hyperparameters and validated with cross-validation.

## Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/HetPatel12/Data-Analytics-on-Loan-Approval.git
   cd Data-Analytics-on-Loan-Approval
   ```
2. `submission.csv` will be generated with loan approval predictions.

## Key Takeaways
- Skills refined: data preprocessing, feature engineering, model optimization.
- Improved understanding of financial metrics in decision-making.
