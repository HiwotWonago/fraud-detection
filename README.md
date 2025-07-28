# Fraud Detection Project – Week 8 & 9

This project was developed by the Data Science team at **Adey Innovations Inc.**, a leading fintech company building advanced solutions for e-commerce and banking fraud prevention. The goal of this project is to improve fraud detection across both e-commerce transactions and bank credit operations using machine learning and model explainability techniques.

---

## Project Overview

We focused on two main datasets:

- **E-commerce Transactions**: Includes user behavioral features, transaction timestamps, and device metadata.
- **Bank Credit Transactions**: Includes customer demographics, account activities, and fraud labels.

---

## Tasks Performed

### 1. Data Preprocessing
- Cleaned missing values and encoded categorical features
- Engineered time-based features like `hour_of_day`, `day_of_week`, and `time_since_signup`

### 2. Model Training Pipelines
- Built end-to-end pipelines using `sklearn.pipeline.Pipeline`
- Trained and evaluated:
  - **Logistic Regression**
  - **XGBoost Classifier**

### 3. Evaluation Metrics
- Accuracy, Precision, Recall, F1-Score, ROC-AUC
- Visualized model performance using confusion matrices and ROC curves


