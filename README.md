# AI Credit Score Predictor

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2.2-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-yellow)

A machine learning system that automatically classifies bank customers' creditworthiness into three risk categories using financial and demographic data.

## Business Context
Banks need automated solutions to:
- Reduce manual review time for credit applications
- Standardize risk assessment across branches
- Minimize default rates while maximizing approvals

## Solution
**Three-class classifier** predicting:
- **Poor** (High risk) - Likely to default
- **Fair** (Medium risk) - Requires manual review
- **Good** (Low risk) - Pre-approved for credit

## Dataset Overview
The dataset contains 15+ features across 50,000+ customer records:

| Feature Category       | Examples                          |
|------------------------|-----------------------------------|
| **Demographics**       | Age, Employment Status, Education|
| **Financial History**  | Loan Count, Payment Delinquencies |
| **Credit Behavior**    | Utilization Rate, Inquiry Count  |
| **Economic Factors**   | Local Unemployment Rate           |

**Target Variable**: `credit_score` (Poor/Fair/Good)

[Download Dataset](https://drive.google.com/drive/folders/1FbDqVq4XLvU85VBlVIMJ73p9oOu6u2-J?usp=drive_link)
