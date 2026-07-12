# Business Understanding

## Project Overview

Insurance fraud is one of the major challenges faced by insurance companies worldwide. Fraudulent claims lead to significant financial losses, increased operational costs, and longer claim processing times.

This project aims to develop an explainable machine learning solution capable of identifying potentially fraudulent insurance claims while providing transparent predictions that can support business decision-making.

---

## Business Problem

Insurance companies receive thousands of claims every day.

Manual investigation of every claim is expensive and time-consuming.

An intelligent fraud detection system can help prioritize suspicious claims for investigation, reducing financial losses while improving operational efficiency.

---

## Business Objectives

The primary objectives of this project are:

- Detect potentially fraudulent insurance claims.
- Minimize financial losses caused by fraud.
- Reduce unnecessary manual investigations.
- Improve claim processing efficiency.
- Provide explainable predictions using SHAP.

---

## Machine Learning Objective

Build a binary classification model that predicts whether an insurance claim is fraudulent.

**Target variable:**

- `fraud_reported`

**Classes:**

- Y → Fraudulent claim
- N → Legitimate claim

---

## Success Criteria

The project will be considered successful if it can:

- Achieve high fraud detection performance.
- Maintain a balance between Precision and Recall.
- Reduce False Negatives (missed fraud cases).
- Produce interpretable predictions.
- Be deployable as an interactive Streamlit application.

---

## Project Methodology

This project follows the CRISP-DM framework:

1. Business Understanding
2. Data Understanding (EDA)
3. Data Preparation
4. Feature Engineering
5. Machine Learning Modeling
6. Model Evaluation
7. Explainability (SHAP)
8. Deployment (Streamlit)

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM
- SHAP
- Streamlit
- Git & GitHub