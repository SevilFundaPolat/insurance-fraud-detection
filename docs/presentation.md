# Insurance Fraud Detection
## Exploratory Data Analysis Presentation

**Author:** Sevil Funda Polat

---

# Slide 1 | Business Understanding

## Business Problem

Insurance fraud is a major challenge for insurance companies worldwide. Fraudulent claims increase financial losses, extend claim processing times, and require costly manual investigations.

## Project Objective

The objective of this project is to explore historical insurance claims, identify patterns associated with fraudulent claims, and prepare the data for machine learning-based fraud detection.

## Dataset

- Source: Mendeley Data
- 1000 insurance claims
- 40 features
- Target variable: `fraud_reported`

## Business Value

- Reduce fraud losses
- Improve claim investigation
- Detect suspicious claims earlier
- Support data-driven decision making

---

# Slide 2 | Dataset Overview

- Records: **1000**
- Features: **40**

Target Distribution

- Fraud (Y): 247 (24.7%)
- Normal (N): 753 (75.3%)

### Finding

The dataset shows a moderate class imbalance but still contains enough fraud cases for predictive modeling.

---

# Slide 3 | Data Quality

## Missing Values

- `_c39` → 100% missing
- `authorities_contacted` → 9.1% missing
- Remaining variables have no missing values.

### Finding

The dataset is relatively clean and requires minimal preprocessing.

---

# Slide 4 | Exploratory Data Analysis

## Main Findings

- Age distributions are similar for fraud and non-fraud claims.
- Fraudulent claims tend to have slightly higher claim amounts.
- Incident severity appears to be strongly associated with fraud.

---

# Slide 5 | Correlation Analysis

Strong correlations include:

- Total Claim Amount ↔ Vehicle Claim
- Total Claim Amount ↔ Property Claim
- Total Claim Amount ↔ Injury Claim
- Age ↔ Months as Customer

### Finding

Several claim-related variables contain overlapping information that should be considered during feature selection.

---

# Slide 6 | Conclusions

## Key Takeaways

- Dataset quality is high.
- Fraud represents approximately 25% of claims.
- Incident severity is one of the strongest indicators.
- Claim-related variables are highly correlated.
- Data is ready for preprocessing and machine learning.