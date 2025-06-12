# AI-Driven Insurance Underwriting with Traditional and Wearable Health Data

## Overview

This project explores the use of Data Science (DS) and Artificial Intelligence (AI) techniques to enhance traditional insurance underwriting by integrating alternative health data such as electronic health records (EHR) and biometric wearables. The goal is to build a predictive, transparent, and responsible model that improves underwriting accuracy, turnaround time, and decision support for insurers.

---

## Objectives

- Predict insurance application approval based on health-related data
- Incorporate both traditional (e.g., age, BMI) and alternative data (e.g., heart rate, sleep)
- Improve operational efficiency and transparency in underwriting decisions
- Apply explainable and responsible AI practices

---

## Data Description

| Data Type        | Features Included                                                 |
|------------------|-------------------------------------------------------------------|
| Traditional      | Age, Gender, BMI, Family Medical History, Blood Glucose Levels    |
| Alternative      | Resting Heart Rate, Sleep Duration, Steps per Day (from wearables)|
| Target Variable  | Application Approved (0 = No, 1 = Yes)                            |

> Note: This project uses simulated data for development and testing purposes.

---

## Tech Stack

- **Python 3.9+**
- `pandas`, `numpy`, `scikit-learn` – Data handling and ML
- `xgboost`, `randomforest` – Model training
- `shap` – Explainable AI
- `matplotlib`, `seaborn` – Visualization
- `Streamlit` (optional) – App interface for model explanation

---

## Model Development Workflow

1. **Data Simulation & Preprocessing**
   - Created a 1000-sample dataset with both traditional and wearable health metrics
   - Cleaned, encoded, and scaled features

2. **Model Training**
   - Trained and evaluated: Logistic Regression, Random Forest, XGBoost
   - Used cross-validation and AUC/Precision/Recall for evaluation

3. **Explainable AI**
   - Applied SHAP to visualize and interpret model decisions
   - Generated global feature importance and local prediction explanations

4. **Insights & Impact**
   - Identified key health indicators (e.g., BMI, sleep hours)
   - Reduced underwriting time while improving decision transparency

---
