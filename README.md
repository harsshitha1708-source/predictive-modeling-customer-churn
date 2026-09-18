# Predictive Modeling Using Machine Learning

## Customer Churn Prediction

### 📌 Project Overview

This project implements a supervised machine learning model to predict
whether a telecom customer is likely to churn.

The model uses customer demographic, service, contract, and billing
information to make predictions.

The project demonstrates the complete machine learning workflow,
including data preprocessing, model training, prediction, and
performance evaluation.

---

## 🎯 Objective

The main objectives of this project are:

- Analyze customer churn data
- Clean and preprocess the dataset
- Handle missing values
- Convert categorical data into numerical features
- Train a machine learning classification model
- Predict customer churn
- Evaluate model performance
- Visualize predictions using a confusion matrix and ROC curve

---

## 📊 Dataset

The project uses the Telco Customer Churn dataset.

The dataset contains:

- 7,043 customer records
- 21 columns
- Customer demographic information
- Services used by customers
- Contract information
- Payment information
- Monthly and total charges
- Customer churn status

### Target Variable

The target variable is:

`Churn`

Where:

- `Yes` → Customer churned
- `No` → Customer stayed

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook
- GitHub

---

## 🤖 Machine Learning Algorithm

### Random Forest Classifier

A Random Forest Classifier was used to predict customer churn.

Random Forest is an ensemble learning algorithm that combines
multiple decision trees to produce a classification result.

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Missing Value Handling
   ↓
Categorical Data Encoding
   ↓
Feature and Target Separation
   ↓
Train-Test Split
   ↓
Random Forest Classifier
   ↓
Predictions
   ↓
Model Evaluation
   ↓
Confusion Matrix
   ↓
ROC Curve and AUC
