# Project-2
Project 2

Objectives

Predict customer churn using machine learning.
Address data imbalance using SMOTE.
Evaluate model performance with a focus on recall.

Dataset

File: telco-customer-churn 2.csv
Size: 7,043 rows, 21 columns.
Features:
Numerical: Tenure, MonthlyCharges, TotalCharges.
Categorical: Gender, Contract, PaymentMethod, etc.
Target: Churn (Yes/No).

Workflow

Data Preparation: Handle missing values, outliers, and encode categorical features.
EDA: Identify correlations and key drivers of churn.
Modeling: Train and evaluate:
Naïve Bayes
Logistic Regression
Random Forests
XGBoost
Evaluation Metrics: Accuracy, Precision, Recall (priority), F1-Score.
Imbalance Handling: Use SMOTE for better class distribution.

Key Findings

Feature Importance: Contract type, tenure, and monthly charges are critical predictors.
Imbalance Handling: SMOTE improved recall across all models.

How to Run

Install dependencies:
pip install -r requirements.txt
Open the notebook:
jupyter notebook Madaka_Project_2.ipynb

Deliverables

Notebook: Madaka_Project_2.ipynb with full analysis and results.
Dataset: telco-customer-churn 2.csv.
Feel free to contribute or suggest improvements!