📉 Telco Customer Churn Prediction using XGBoost Classifier
📋 Overview

This project predicts customer churn (whether a telecom customer will leave or stay) using a powerful XGBoost Classifier model.

Telecom churn prediction is crucial for identifying customers who are likely to leave, so the company can take early retention actions, improve customer satisfaction, and reduce revenue loss.

🎯 Project Objectives

Analyze telecom customer behavior

Identify factors that contribute to churn

Build a highly accurate machine learning model using XGBoost

Preprocess and encode telecom dataset features

Evaluate with confusion matrix, classification report, and accuracy

Save the model and preprocessing pipeline for deployment

Deploy prediction using a Streamlit app

📂 Dataset Description

The dataset contains telecom customer information, including:

Sample Features

customerID

gender

SeniorCitizen

Partner

Dependents

tenure

PhoneService

InternetService

OnlineBackup

TechSupport

Contract

PaperlessBilling

PaymentMethod

MonthlyCharges

TotalCharges

Churn (Target variable → 1 = Churned, 0 = Stayed)

🧪 Technologies Used

Python

Pandas, NumPy – Data preprocessing

Scikit-learn – Encoding, scaling, splitting, evaluation

XGBoost – Classification model

Joblib – Saving model & preprocessor

Matplotlib, Seaborn – Visualizations

⚙️ Data Preprocessing Steps

✔ Handle missing values
✔ Convert TotalCharges to numeric
✔ Encode categorical variables using OneHotEncoder
✔ Scale numerical features using StandardScaler
✔ Train-test split

🚀 Model: XGBoost Classifier
Why XGBoost?

Handles categorical data well (after encoding)

Great for imbalanced datasets

High accuracy and fast training

Excellent generalization
