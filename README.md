# 📞 Telecom Customer Churn Prediction

This project aims to predict customer churn for a telecom company using machine learning. By identifying customers who are at high risk of leaving, telecom companies can proactively implement retention strategies and reduce customer loss.

---

## 📌 Problem Statement

Churn, or customer attrition, is a major concern for telecom companies. The goal of this project is to:

- Predict whether a customer will churn or not.
- Identify the key factors influencing churn.
- Enable business decisions that can reduce churn and improve customer loyalty.

---

## 🧰 Tools & Technologies

- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Machine Learning Algorithms**: Logistic Regression, Random Forest, XGBoost
- **SMOTE** for class imbalance handling
- **SHAP** for model explainability
- Jupyter Notebook

---

## 📊 Data Description

The dataset contains customer-level information such as:

- Demographics (gender, senior citizen, partner, dependents)
- Account information (contract type, payment method, tenure)
- Services used (internet, phone, streaming, tech support)
- Charges (monthly, total)

---

## 🔍 Exploratory Data Analysis

- Customers with **monthly contracts** are more likely to churn.
- **High monthly charges** and **low tenure** increase churn risk.
- Lack of **tech support** and use of **fiber optic internet** also correlate with churn.

---

## 🛠️ Data Preprocessing

- Handled missing values and corrected data types.
- Used **One-Hot Encoding** for categorical features.
- Applied **SMOTE** to address class imbalance in churn labels.

---

## 🤖 Model Building

Three models were trained and evaluated:

| Model               | Accuracy | ROC AUC |
|--------------------|----------|---------|
| Logistic Regression| ~79%     | 0.83    |
| Random Forest      | ~83%     | 0.88    |
| **XGBoost**         | **~85%** | **0.91** |

---

## 📈 Model Evaluation Metrics

- **Confusion Matrix**
- **Precision, Recall, F1-Score**
- **ROC-AUC Score**

---

## 🧠 Model Explainability

- Used **SHAP** values to understand model predictions.
- Top factors contributing to churn:
  - Contract Type (monthly)
  - Tenure
  - Monthly Charges
  - Tech Support availability

---

## 💼 Business Impact

- Identified a segment of customers (~15%) at high churn risk.
- Enabled targeted campaigns to improve retention and customer engagement.
- Potential cost savings by reducing churn with proactive outreach.
