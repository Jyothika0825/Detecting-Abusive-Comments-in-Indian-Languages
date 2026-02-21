# Detecting Abusive Comments in Hindi

## Overview
This project focuses on detecting abusive and non-abusive comments in Hindi using Natural Language Processing (NLP) techniques.

The model uses:
- TF-IDF feature extraction
- Logistic Regression
- Multinomial Naive Bayes

## Dataset
Dataset: Hindi Abusive Comments Dataset  
Source: Kaggle (Multilingual Abusive Comment Classification)

Columns used:
- commentText
- label
- language

Data Split:
- 60% Training
- 25% Validation
- 15% Testing

## Models Used

1. Logistic Regression (L2 Regularization)
2. Multinomial Naive Bayes

## Evaluation Metrics
- Accuracy
- Precision
- Recall (Sensitivity)
- Specificity
- F1 Score
- ROC-AUC

## Results
Logistic Regression showed stronger and more stable performance compared to Naive Bayes.

## How to Run

1. Install requirements:
   pip install -r requirements.txt

2. Run:
   python hindi_abuse_detection_full.py

## Author
JYOTHIKA UDUGULA