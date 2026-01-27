# Credit Risk Analysis and Prediction

## Overview
This repository contains the implementation of a **Credit Risk Analysis and Prediction** project developed as part of an undergraduate graduation thesis in **Data Science**.

The objective of this project is to build machine learning models that can predict the **probability of credit default** based on customer information and historical credit data, thereby supporting better decision-making in credit approval and risk management.

---

## Problem Statement
Credit risk prediction is a binary classification problem where customers are classified as:
- **0**: Non-default (creditworthy)
- **1**: Default (high credit risk)

Incorrect predictions may lead to financial losses:
- Rejecting good customers reduces potential profit.
- Approving risky customers increases default risk.

This project aims to develop accurate and reliable predictive models while maintaining interpretability, which is crucial in financial applications.

---

## Dataset
- The dataset is derived from the **Home Credit Default Risk** problem.
- It includes customer demographic information, loan characteristics, and historical credit behavior.
- Due to data size and privacy concerns, raw data is **not included** in this repository.

---

## Methodology
The project follows a standard end-to-end data science pipeline:

1. **Data Preparation**
   - Data cleaning and missing value handling
   - Feature aggregation from multiple related tables
   - Feature selection and transformation

2. **Exploratory Data Analysis (EDA)**
   - Distribution analysis
   - Correlation analysis
   - Class imbalance inspection

3. **Handling Class Imbalance**
   - Techniques such as resampling and class weighting

4. **Model Development**
   - Logistic Regression
   - Random Forest
   - XGBoost
   - LightGBM
   - CatBoost
   - Stacking Ensemble

5. **Model Optimization**
   - Hyperparameter tuning
   - Classification threshold optimization

6. **Model Evaluation**
   - Precision
   - Recall
   - F1-score
   - AUC-ROC
   - Gini coefficient

7. **Explainable AI (XAI)**
   - SHAP for global feature importance
   - LIME for local model explanations

---

## Models Used
- Logistic Regression
- Random Forest
- XGBoost
- LightGBM
- CatBoost
- Stacking Ensemble

These models are compared to identify the best-performing approach in terms of predictive power and stability.

---

## Results
- Ensemble and boosting-based models outperform traditional statistical models.
- Threshold optimization significantly improves F1-score and recall.
- Explainability techniques help interpret model decisions and increase transparency.

Detailed experimental results and analysis are presented in the thesis report.

---

## Technologies
- Python
- NumPy, Pandas
- Scikit-learn
- XGBoost, LightGBM, CatBoost
- SHAP, LIME
- Matplotlib, Seaborn
