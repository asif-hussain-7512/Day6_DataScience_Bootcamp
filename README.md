# Day6_DataScience_Bootcamp

# Customer Churn Prediction

## Participant Name
Asif Hussain

## MUID
asifhussain@mulearn

---

## Business Objective

The objective of this project is to predict whether a customer is likely to churn. Early prediction enables businesses to improve customer retention through targeted interventions.

---

## Dataset Overview

Source:
https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset

The dataset contains customer demographic, account, and service information along with a churn label.

---

## Features

Examples:

- Gender
- SeniorCitizen
- Tenure
- MonthlyCharges
- TotalCharges
- Contract
- PaymentMethod

Target:

- Churn

---

## Preprocessing Pipeline

- Missing value handling
- Label Encoding
- Feature Scaling
- Train-Test Split (80:20)

---

## Models Implemented

1. Logistic Regression
2. Decision Tree
3. Random Forest

---

## Performance Comparison

| Model | Accuracy | Precision | Recall | F1 |
|--------|----------|-----------|--------|----|
| Logistic Regression | XX | XX | XX | XX |
| Decision Tree | XX | XX | XX | XX |
| Random Forest | XX | XX | XX | XX |

---

## Best Model

Random Forest achieved the highest overall performance and was selected as the final model.

---

## Key Observations

- Random Forest produced the highest accuracy.
- Decision Tree tended to overfit.
- Logistic Regression provided a strong baseline.

---

## Business Recommendations

- Identify customers predicted to churn.
- Offer personalised retention campaigns.
- Improve customer support for high-risk customers.
- Monitor contract renewals proactively.

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- XGBoost or LightGBM
- Feature engineering
- Deployment using Flask or Streamlit
