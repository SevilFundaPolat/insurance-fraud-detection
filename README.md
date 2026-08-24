# 🛡️ Insurance Fraud Detection using Explainable Machine Learning


## Project Overview

Insurance fraud is a major challenge for insurance companies, leading to financial losses, increased investigation costs, and inefficient claim processing.

This project aims to develop an end-to-end Machine Learning solution for detecting potentially fraudulent insurance claims and supporting investigators in prioritizing higher-risk cases.

The project follows a structured Data Science workflow, combining business understanding, exploratory data analysis, data quality assessment, feature selection, feature engineering, preprocessing, model development, model evaluation, and explainability.

The primary objective is not to replace human fraud investigators, but to provide a predictive decision-support tool that can help allocate investigative resources more efficiently.



## Business Problem

Insurance companies process a large number of claims, while only a proportion of them are fraudulent.

Investigating every claim manually can be expensive, time-consuming, and difficult to scale.

A Machine Learning model can help identify claims with a higher predicted probability of fraud, allowing investigators to prioritize cases for further review.

This project therefore addresses a binary classification problem:

- **Fraudulent claim**
- **Non-fraudulent claim**

The target variable is `fraud_reported`.



## Project Objectives

The main objectives of the project are to:

- Understand the business problem and the structure of insurance claims data
- Assess data quality and identify potential inconsistencies
- Explore numerical and categorical variables
- Examine the distribution of the fraud target
- Identify redundant and highly correlated features
- Perform feature selection using the training data only
- Engineer meaningful temporal and claim-related features
- Handle missing values appropriately
- Transform categorical variables into numerical representations
- Develop and compare Machine Learning models
- Evaluate model performance using appropriate classification metrics
- Investigate model explainability using SHAP
- Develop a potential Streamlit application for model demonstration

---

## Dataset

The project uses the **Insurance Claims dataset** published on Mendeley Data.

**Source:**  
https://data.mendeley.com/datasets/992mh7dk9y/2

Each observation represents an individual insurance claim.

The dataset contains information related to:

- Policy characteristics
- Customer demographics
- Insurance coverage
- Claim amounts
- Incident characteristics
- Vehicle information
- Claim processing information
- Fraud investigation outcomes

The target variable is:

```text
fraud_reported
