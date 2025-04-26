# Financial-Fraud-Detection

Detecting fraudulent transactions using machine learning on a 6.3M-row dataset.

## Overview
This project builds a high-recall fraud detection system using Python (XGBoost) and Power BI. It tackles severe class imbalance while modeling behavior-based patterns in financial transaction data.

## Dataset
- 6.3M real-world transactions
- Includes fields like: `amount`, `transaction type`, `balance origin`, `balance destination`, `isFraud`

## Features Engineered
- Origin & destination balance deltas
- Net transaction effect
- Transaction type encoding
- Scaled financial amounts

## Model Pipeline
- Data cleaning & preprocessing
- Label encoding + scaling
- Train/validation/test split
- Model training (XGBoost, class weighting)
- Evaluation: ROC-AUC, recall, precision, F1
- Class imbalance handled using `class_weight`

## Results
- ROC-AUC: **99.97%**
- Recall on fraud class: **99.2%**

## Power BI Dashboard
Includes:
- Fraud detection over time
- High-risk transactions
- Prediction confidence breakdown

## Tools & Libraries
`Python`, `pandas`, `XGBoost`, `scikit-learn`, `matplotlib`, `seaborn`, `Power BI`

---
