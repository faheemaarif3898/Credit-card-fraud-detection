# Credit Card Fraud Detection

This project addresses credit card fraud detection using a highly imbalanced transaction dataset from Kaggle.

A Random Forest classifier with class weighting and threshold tuning is used to balance fraud detection recall against false positives.

## Key Techniques
- Stratified train–test split
- Class-weighted Random Forest
- Probability-based threshold tuning
- Precision–Recall evaluation

## Results
- Fraud Precision: ~0.77
- Fraud Recall: ~0.84
- ROC-AUC: ~0.98
- PR-AUC: Reported

## Tools
- Python
- pandas
- scikit-learn
- matplotlib, seaborn

## Dataset
Kaggle Credit Card Fraud Detection dataset.
