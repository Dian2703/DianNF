# Loan Default Risk Prediction

This project develops a predictive model to identify loan applicants who are likely to default, helping financial institutions manage risk more effectively.

# Dataset
- **Source**: Home Credit Default Risk dataset  
- **Total rows**: 307,511  
- **Features used**: 13 selected numeric features with low missing values

# Model
- **Algorithm**: Logistic Regression  
- **Preprocessing**:
  - Median imputation for missing values  
  - Feature scaling with StandardScaler  
- **Hyperparameter**: GridSearchCV  
  - `C = 0.1`  
  - `penalty = 'l1'`  
- **Performance**:  
  - **ROC AUC Score**: 0.76

# How to Run
1. Clone the repository  
2. Open the notebook using Jupyter or VS Code  
3. Run all cells to see the analysis and prediction results
