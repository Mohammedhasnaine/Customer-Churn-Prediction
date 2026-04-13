# Customer Churn Prediction Model

## Business Problem
Telecom companies lose significant revenue when customers cancel their subscriptions.
This project builds a machine learning model to predict which customers are likely 
to churn — allowing businesses to intervene early with retention offers.

## Dataset
- Source: IBM Telco Customer Churn Dataset
- Size: 7,043 customers, 20 features
- Target: Churn (Yes/No)

## Approach
1. Data cleaning and preprocessing
2. Handled class imbalance using SMOTE (73% / 27% → 50% / 50%)
3. Trained and compared 3 models: Logistic Regression, Random Forest, XGBoost
4. Selected best model based on accuracy and classification report

## Results
| Model | Accuracy |
|-------|----------|
| Logistic Regression | 75.94% |
| Random Forest | 77.00% |
| XGBoost | 76.86% |

**Best Model: Random Forest — 77% Accuracy**

## Key Findings
- Month-to-month contract customers are the highest churn risk
- Customers with Fiber optic internet and no security addons churn more
- Low tenure (new customers) are significantly more likely to churn

## Tools Used
Python, Pandas, Scikit-learn, XGBoost, Imbalanced-learn, Seaborn, Matplotlib
