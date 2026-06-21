# Credit Risk Prediction System

## Project Overview

This project is an end-to-end Machine Learning application that predicts whether a loan applicant is likely to be a low-risk or high-risk borrower based on financial and demographic information. The objective is to assist financial institutions in making informed loan approval decisions and reducing default risk.

## Features

* Data Cleaning and Preprocessing
* Missing Value Treatment
* Feature Engineering
* Exploratory Data Analysis (EDA)
* Multiple Machine Learning Models
* Hyperparameter Tuning
* Model Evaluation and Comparison
* Interactive Streamlit Web Application
* Cloud Deployment using Streamlit Community Cloud

## Dataset

The project uses the Loan Prediction dataset containing applicant information such as:

* Gender
* Marital Status
* Dependents
* Education
* Employment Status
* Applicant Income
* Co-applicant Income
* Loan Amount
* Loan Term
* Credit History
* Property Area

Target Variable:

* Loan Status (Approved / Rejected)

## Machine Learning Workflow

1. Data Understanding
2. Data Preprocessing
3. Feature Engineering
4. Exploratory Data Analysis
5. Model Training
6. Hyperparameter Optimization
7. Model Evaluation
8. Model Deployment

## Models Implemented

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier

The best-performing model was selected and deployed for real-time predictions.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Streamlit
* GitHub

## Live Demo

Streamlit Application:

https://credit-risk-prediction-mzq42aretyrikjxd6d4gqd.streamlit.app/

## Project Structure

```text
Credit-Risk-Prediction/
│
├── app.py
├── credit_risk_model.pkl
├── requirements.txt
├── train_u6lujuX_CVtuZ9i.csv
└── README.md
```

## Results

The deployed application allows users to enter applicant details and receive an instant prediction regarding loan approval risk. The system demonstrates a complete Machine Learning pipeline from data preprocessing to cloud deployment.

## Learning Outcomes

Through this project, I gained practical experience in:

* Data Preprocessing and Feature Engineering
* Exploratory Data Analysis
* Machine Learning Model Development
* Model Evaluation and Optimization
* Model Serialization using Pickle
* Web Application Development with Streamlit
* Cloud Deployment and Version Control using GitHub
