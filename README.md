# Customer Churn Prediction

A machine learning project that predicts which telecom customers are likely 
to cancel their subscription — helping businesses retain revenue proactively.

---

## Problem Statement
Telecom companies face heavy losses due to customer churn. Identifying 
at-risk customers early allows targeted retention campaigns before it's too late.

---

## What This Project Does
- Cleans and preprocesses raw telecom customer data
- Handles severe class imbalance using SMOTE
- Trains and compares Logistic Regression, Random Forest, and XGBoost
- Delivers a simple prediction function: input one customer → get churn risk %

---

## Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 75.94% |
| Random Forest | 77.00% ✓ Best |
| XGBoost | 76.86% |

---

## How to Run
1. Clone this repository
2. Install dependencies
3. Open `churn_model.ipynb` in Jupyter
4. Run all cells top to bottom

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
```

---

## Tech Stack
Python · Pandas · Scikit-learn · XGBoost · SMOTE · Seaborn · Matplotlib

---

## Business Use Case
This model can be directly integrated into a CRM system to flag high-risk 
customers automatically every month.
