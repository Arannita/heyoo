# Credit Card Fraud Detection — Exploratory Data Analysis (COMP714)

This folder contains the **fully executed** EDA-only assignment from the original ULB/Worldline credit-card fraud dataset (284,807 observations, 31 source fields). No predictive models have been trained.

## Deliverables
- [Executed Jupyter Notebook (.ipynb)](Credit_Card_Fraud_EDA.ipynb) — all 11 code cells executed without errors, nine chart figures and written interpretations.
- [Notebook printout (PDF)](Credit_Card_Fraud_EDA.pdf) — exported from the executed notebook.
- [Notebook generation script](generate_notebook.py) — reproducible notebook source code.

## Data and method
The published notebook was executed against the full dataset. The input CSV (~150 MB) is **not stored in GitHub** due to file size. For reruns, the notebook fetches the complete data from a public archival mirror, then verifies the 284,807 × 31 source shape.

Original source: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Archived dataset metadata: https://zenodo.org/records/7395559

The notebook documents types, missingness, duplicates, imputation policy, distributional checks, class imbalance, amount tails, time-based patterns, and PCA feature associations. All transformations are exploratory, with no model fitting or class balancing.

## Submission
Submit `Credit_Card_Fraud_EDA.ipynb`, `Credit_Card_Fraud_EDA.pdf`, and this public GitHub folder URL to Canvas.
