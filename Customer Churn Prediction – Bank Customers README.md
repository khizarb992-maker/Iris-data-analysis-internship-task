 Customer Churn Prediction – Bank Customers

Objective
The goal of this project is to predict which bank customers are likely to leave. By identifying potential churners, the bank can take proactive measures to retain valuable customers.

 Dataset
Churn Modelling Dataset
- Includes customer demographic and account-related features such as:
  - CreditScore, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary
  - Categorical features: Gender, Geography
  
 Data cleaning
- Handled missing values and removed irrelevant columns.
- Encoded categorical features:
  - Gender → Label Encoding
  - Geography → One-Hot Encoding (dropping first category to avoid dummy variable trap)

 Model Building
- Split dataset into training and testing sets.
- Trained a Random Forest Classifier for supervised classification.
- Evaluated model performance using:
  - Accuracy
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)

 Feature Importance
Analyzed feature importance to understand which factors influence churn.
Key influential features typically include:
- CreditScore
- Balance
- NumOfProducts
- Geography
- Age

 Skills Applied
- Categorical Data Encoding: Label Encoding & One-Hot Encoding
- Supervised Classification Modeling: Random Forest Classifier
- Feature Importance Analysis: Identifying key drivers of customer churn
- Evaluation Metrics: Accuracy, Confusion Matrix, Classification Report
