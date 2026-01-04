Loan Approval Prediction using Logistic Regression
📌 Project Overview

This project is a Machine Learning classification application that predicts whether a loan will be approved or not based on applicant details.
The model is built using Logistic Regression and deployed as an interactive web application using Streamlit.

🚀 Features

Interactive Streamlit web interface

Logistic Regression classification model

Feature scaling using StandardScaler

Model evaluation using:

Accuracy

Confusion Matrix

Classification Report

Real-time loan approval prediction

🧠 Machine Learning Workflow

Data loading and preprocessing

Feature–target separation

Train-test split

Feature scaling

Logistic Regression model training

Model evaluation

Prediction on new user inputs

Deployment using Streamlit

📊 Dataset Description

The dataset contains applicant information such as:

Feature	Description
Age	Applicant age
Income	Annual income
Loan Amount	Requested loan amount
Credit Score	Applicant credit score
Target	Loan Approved (0 = No, 1 = Yes)
🧪 Model Used

Algorithm: Logistic Regression

Type: Supervised Learning (Binary Classification)

Why Logistic Regression?

Suitable for binary outcomes

Outputs probability scores

Simple and interpretable

📈 Model Performance
✅ Accuracy

The Logistic Regression model achieved an accuracy of:

Accuracy: ~85% (may vary based on dataset split)


Accuracy represents the percentage of correctly predicted loan approval decisions on unseen test data.

📊 Evaluation Metrics Used

Accuracy Score

Confusion Matrix

Precision, Recall, F1-Score

These metrics provide a deeper understanding of model performance beyond accuracy.

🖥️ Tech Stack

Language: Python

Libraries:

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Streamlit

📂 Project Structure
Loan_Approval_Prediction/
│
├── logistic.py        # Streamlit app with Logistic Regression
├── data.csv           # Dataset
├── README.md          # Project documentation
└── requirements.txt   
