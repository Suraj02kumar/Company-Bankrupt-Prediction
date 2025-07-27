# Company-Bankrupt-Prediction using Logistic Regression and Support Vector machine

# Project Overview
This project aims to predict whether a company will go bankrupt based on historical financial performance data collected from the Taiwan Economic Journal (1999–2009). The dataset contains 6819 records and 96 features, including financial ratios like return on assets, gross margin, debt ratio, and more.
The target variable is:
Y = 1 → Bankrupt
Y = 0 → Not Bankrupt


# Exploratory Data Analysis (EDA)
Shape of Dataset: (6819, 96)
Null Values: 0
Duplicate Rows: 0
Data Type: All columns are numerical
Target Column: Y

# Data Preparation
Splitting Data:
Features X = All columns except Y
Target y = Column Y
Train-Test Split: 80% training and 20% testing

# Feature Scaling: Standardization using StandardScaler
(important for SVM and Logistic Regression performance)

# Model Building
Logistic Regression:
Trained with max_iter=1000 for convergence
Evaluated on test set

Support Vector Machine (SVM):
Kernel: 'rbf' (Radial Basis Function)
Also trained on standardized data

 This project demonstrates how financial ratios and machine learning can be used to assess the risk of bankruptcy, an important task in finance and credit risk assessment.
