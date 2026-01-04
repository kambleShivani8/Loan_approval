Loan Approval Prediction using Logistic Regression
📌 Project Overview

This project is a Machine Learning classification application that predicts whether a loan will be approved or not based on applicant details.
The model is built using Logistic Regression and deployed as an interactive web application using Streamlit.

The goal of this project is to demonstrate:

End-to-end ML workflow

Classification modeling

Model evaluation

Deployment using Streamlit

🚀 Features

User-friendly Streamlit web interface

Logistic Regression classification model

Feature scaling using StandardScaler

Model evaluation using:

Accuracy

Confusion Matrix

Classification Report

Real-time loan approval prediction

🧠 Machine Learning Workflow

Data loading and inspection

Feature–target separation

Train-test split

Feature scaling

Logistic Regression model training

Model evaluation

Prediction on new user inputs

Web app deployment using Streamlit

📊 Dataset Description

The dataset contains applicant details such as:

Feature	Description
Age	Applicant age
Income	Annual income
Loan Amount	Requested loan amount
Credit Score	Applicant credit score
Target	Loan Approved (0 = No, 1 = Yes)

Note: Target variable is binary (0/1), suitable for Logistic Regression.

🧪 Model Used

Algorithm: Logistic Regression

Type: Supervised Learning (Classification)

Why Logistic Regression?

Suitable for binary classification

Outputs probability

Interpretable model

📈 Model Evaluation Metrics

Accuracy Score

Confusion Matrix

Precision, Recall, F1-Score (Classification Report)

These metrics help analyze model performance beyond accuracy.

🖥️ Tech Stack

Programming Language: Python

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
└── requirements.txt   # Required libraries
