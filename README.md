# telco-customer-churn
Data Science project to predict customer churn using demographic and behavioral data. Built with Python, scikit-learn, pandas, and seaborn.

Telco Customer Churn Prediction

Project Overview

This project aims to predict customer churn for a telecom company using demographic information and customer behavior data. Identifying customers likely to leave the service helps improve retention strategies and reduce churn-related losses.

Dataset

Source: Kaggle - Telco Customer Churn https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data
Size: 7,043 customer records
Features: Demographics (gender, senior citizen, partner, dependents), service usage (Internet, phone), billing details (monthly and total charges), contract type, and churn label

Key Steps
- Data Cleaning: Handled missing values and corrected data types

Exploratory Data Analysis (EDA):
- Compared churn distribution by gender, contract type, tenure, and charges
- Used visualizations (boxplots, countplots, pairplots) to understand patterns

Class Balancing:
- Applied SMOTE to address class imbalance between churners and non-churners

Feature Encoding:
- Converted categorical features using One-Hot Encoding

Model Training:
- Used Logistic Regression, Random Forest, Gradient Boosting

Model Evaluation:
- Accuracy: 78%
- AUC-ROC: 0.82
- F1-score: Balanced between churn and no-churn classes

Key Findings
- Customers with month-to-month contracts are more likely to churn
- Lower tenure is strongly associated with higher churn probability
- Higher monthly charges correlate with churn
- OnlineSecurity and TechSupport availability reduce the likelihood of churn

Visual Insights
- Heatmap of feature correlations with churn
- Pairplots showing separation between churners and non-churners
- Boxplots for MonthlyCharges and Tenure by churn

Technologies Used

- Python
- pandas, seaborn, matplotlib
- scikit-learn (SMOTE, modeling, evaluation)
