# LOAN DEFAULT PREDICTION MODEL 
## Overview

This project implements a machine learning–based Probability of Default (PD) model to classify borrowers into high-risk and low-risk categories using historical loan data. The objective is to support risk-aware lending decisions through model comparison, performance evaluation, and monitoring.

## Business Problem

Loan defaults pose a major financial risk for lending institutions. Traditional rule-based systems often fail to capture complex borrower behavior.

Goal:
Predict the likelihood of borrower default to enable:

Risk-based credit approvals

Better identification of high-risk applicants

Improved portfolio quality

## Approach & Methodology

Performed data preprocessing and feature preparation on historical loan data

Benchmarked Logistic Regression, Random Forest, and XGBoost classification models

Selected XGBoost as the final model based on performance trade-offs

Evaluated model performance using accuracy, precision, recall, F1-score, and confusion matrix

## Model Performance (Final Model)

Accuracy: 92%

High-risk (Default) class precision: Strong precision to minimize false approvals

Evaluation focus: Business-relevant classification metrics rather than accuracy alone

## Model Monitoring Dashboard

To simulate real-world deployment, a classification model monitoring dashboard was built to:

Track key performance indicators (KPIs)

Visualize the confusion matrix

Compare predicted vs actual loan outcomes

Support ongoing model performance evaluation

## Tools & Technologies

Python (Pandas, NumPy, Scikit-learn)

XGBoost

Power BI / Visualization tools (for dashboarding)

Jupyter Notebook
