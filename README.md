# Telco Customer Churn Prediction

A machine learning project to predict whether a telecom customer will churn (leave the company) or not, based on their account and service details.

## Dataset

- **Source:** [Telco Customer Churn (IBM dataset)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **File:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- Contains ~7,000 fictional customers with demographic info, subscribed services, account details, and whether they churned.

## Goal

Build a binary classification model to predict the `Churn` column (Yes/No) using the other customer features.

## Models Used

- Logistic Regression (baseline)
- Random Forest Classifier
- XGBoost Classifier

## Project Status

🚧 In progress — data preprocessing and model training not completed yet.

## Steps (planned)

1. Load and explore the dataset
2. Clean data (handle missing values, encode categorical features)
3. Split into train/test sets
4. Train Logistic Regression, Random Forest, and XGBoost
5. Compare models using accuracy, precision, recall, F1, and ROC-AUC
6. Identify the most important features driving churn

## Results


## Technical Requirements

- Python
- pandas
- scikit-learn
- XGBoost
- matplotlib
