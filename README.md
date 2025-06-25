# customer-churn-prediction
# 📊 Customer Churn Prediction - Telecom

## 📌 Objective
Predict whether a customer will churn (leave the telecom company) using machine learning.

## 📁 Dataset
Source: [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)

## 💡 Key Concepts Learned
- Data Cleaning & Preprocessing
- Label and OneHot Encoding
- Feature Scaling using StandardScaler
- Model Building: Logistic Regression, Random Forest
- Model Evaluation
- Feature Importance Analysis
- Model Saving with joblib

## 🛠 Tools Used
- Python (Jupyter Notebook)
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn,joblib

- WHY WE USED THESE TECHNIQUES?
Technique	Reason
LabelEncoder	For binary categorical values (Yes/No)
OneHotEncoder	For non-binary categorical features (like Contract)
StandardScaler	To normalize feature range for models like Logistic Regression
RandomForestClassifier	Handles both classification and feature importance well
joblib	Efficiently saves ML models for reuse/deployment

## 🚀 How to Run
1. Clone this repo
2. Install dependencies using:
