# 💼 Personal Loan Acceptance Prediction

## 📌 Project Overview

This project is used to predict whether a customer will accept a personal loan offer using the Bank Marketing Dataset. By analyzing customer demographics and financial conditions, we build classification models to identify potential loan subscribers.


 🎯 Objective

* Predict customer response (Yes/No) to a personal loan offer
* Understand which features influence loan acceptance
* Provide actionable insights for targeted marketing

 📂 Dataset

* Source: Kaggle data set
* Dataset Name: Bank Marketing Dataset
* Contains customer information such as:

  * Age
  * Job
  * Marital status
  * Education
  * Balance
  * Loan history

 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn


 🔍 Data Exploration

Performed exploratory data analysis (EDA) on key features:

 ✔ Age

* Most customers fall between **30–50 years**
* Middle-aged individuals show higher loan acceptance

 ✔ Job

* Customers in management and administrative roles are more likely to accept loans
* Blue-collar jobs show lower acceptance rates

 ✔ Marital Status

* Married customers tend to accept loans more frequently
* Singles and divorced customers show varied behavior


 ⚙️ Data Preprocessing

* Handled categorical variables using Label Encoding
* Checked for missing values
* Applied feature scaling (StandardScaler) to improve model performance

 🤖 Models Used

 1. Logistic Regression


 2. Decision Tree Classifier


 📊 Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report (Precision, Recall, F1-score)


 📈 Results

* Logistic Regression performed well with stable predictions
* Decision Tree captured patterns but required tuning
* Feature scaling significantly improved Logistic Regression performance


 🧠 Key Insights

* Customers with higher account balances are more likely to accept loans
* Profession plays a major role in loan acceptance
* Customers without existing loans are more open to new offers
* Targeting the right segment can improve marketing efficiency

 🚀 Conclusion

This project demonstrates how machine learning can help financial institutions:

* Identify potential customers
* Improve marketing strategies
* Increase loan conversion rates
