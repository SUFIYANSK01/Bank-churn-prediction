# Bank-churn-prediction
A Machine Learning project to predict customer churn in banks# 🏦 Bank Churn Prediction

This project aims to build a machine learning model to predict customer churn for a bank — identifying customers who are likely to leave the bank in the near future. Accurate churn prediction helps banks proactively improve customer retention and reduce revenue loss.

---

## 📌 Project Overview

- **Problem Statement**: Predict whether a customer will churn (exit the bank) based on various features such as credit score, geography, age, tenure, balance, number of products, etc.
- **Goal**: Use machine learning algorithms to classify customers as "churn" or "not churn".
- **Tools Used**: Python, Google Colab, Pandas, NumPy, Matplotlib, Scikit-Learn, Seaborn

---

## 🧠 Machine Learning Approach

### 🔹 Steps Followed:
1. **Data Cleaning & Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Engineering**
4. **Model Training**
5. **Model Evaluation**
6. **Performance Comparison**

### 🔹 Algorithms Used:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Support Vector Machine (SVM)

---

## 📊 Dataset Information

- **Source**: [Kaggle - Bank Customer Churn Dataset](https://www.kaggle.com/datasets/adammaus/predicting-churn-for-bank-customers)
- **Records**: 10,000 customers
- **Target Variable**: `Exited` (1 = customer left, 0 = customer stayed)

### 🔹 Features:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

---

## 📈 Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## 🏁 Final Results

| Model              | Accuracy | F1 Score | ROC-AUC |
|-------------------|----------|----------|---------|
| Logistic Regression | 0.80     | 0.57     | 0.77    |
| Random Forest       | 0.86     | 0.65     | 0.84    |
| XGBoost             | **0.87** | **0.66** | **0.85** |

✅ **XGBoost** performed best in terms of accuracy and generalization.

---

## 🛠️ Installation & Running

1. Clone the repo:
   ```bash
   git clone https://github.com/SUFIYSNSK01/bank-churn-prediction.git


