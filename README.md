# Credit Card Fraud Detection 💳🔍

This project uses **Logistic Regression** to detect fraudulent credit card transactions. It demonstrates how to deal with class imbalance using data preprocessing and evaluates the model using key performance metrics.

## 🎯 Objective
Develop a machine learning model that can accurately classify transactions as fraudulent or legitimate.

## 📊 Dataset
- **Source**: European cardholder transaction data (2 days in September 2013)
- **Total transactions**: 284,807  
- **Fraudulent transactions**: 492 (~0.17%) — extremely imbalanced
- Features are anonymized (V1 to V28) via PCA, except for `Time` and `Amount`.

## 🛠️ Tools & Libraries
- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Sklearn
- imbalanced-learn (SMOTE)

## ⚙️ ML Model Used
- **Logistic Regression**

## ⚖️ Handling Imbalance
- Applied **SMOTE (Synthetic Minority Oversampling Technique)** to oversample the minority class (fraud cases).

## 📈 Evaluation Metrics
- Confusion Matrix
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Curve

## 🧪 Results Summary
- Logistic Regression performed well after applying SMOTE.
- Improved recall ensured more frauds were correctly detected.
