# Credit-Card-Fraud-Detection-Project
To build a machine learning model that can accurately detect fraudulent credit card transactions based on historical transaction data.
Credit card fraud is one of the most significant issues in the finance sector. With the rise of online transactions, detecting fraudulent activities in real-time has become a challenge. This project uses machine learning techniques to analyze transaction patterns and classify whether a transaction is fraudulent or not.

📊 Dataset:
Name: Credit Card Fraud Detection Dataset

Source: Kaggle

Size: ~284,807 transactions

Features:

Time, V1 to V28: Anonymized PCA components

Amount: Transaction amount

Class: Target variable (0 = Non-fraud, 1 = Fraud)

🧠 Tech Stack:
Language: Python

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, imbalanced-learn

🔄 ML Workflow:
1. Data Preprocessing:
Load the dataset

Handle class imbalance (undersampling or oversampling using SMOTE)

Feature scaling (StandardScaler)

Train-test split

2. Model Building:
Try different ML algorithms:

Logistic Regression

Random Forest

Decision Tree

XGBoost

Support Vector Machine

3. Evaluation Metrics:
Confusion Matrix

Accuracy

Precision

Recall

F1-Score

ROC-AUC Curve
