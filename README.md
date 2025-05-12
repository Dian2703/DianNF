# Loan Default Risk Prediction

This project builds a predictive model to identify loan applicants who are likely to default.

# Dataset
- Source: Home Credit Default Risk 
- Rows: 307,511
- Features used: 13 selected numeric features with low missing values

# Model
- Algorithm: Logistic Regression
- Preprocessing: Median Imputation + StandardScaler
- Tuning: GridSearchCV (C=0.1, penalty=l1)
- ROC AUC: 0.76
