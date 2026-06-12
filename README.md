# Spam SMS Classification

A Machine Learning project to detect **Spam** vs **Ham** messages using NLP and Random Forest.

## Overview
- Dataset: SMS Spam Collection (5572 messages)
- Best Model: Random Forest Classifier
- F1-Score: **0.994**

## Workflow
- Exploratory Data Analysis
- Text Preprocessing (Cleaning, Lemmatization, TF-IDF)
- Oversampling to fix class imbalance
- Model Training & Evaluation

## Models Tested
- Decision Tree
- Random Forest (Best)
- Multinomial Naive Bayes
- Voting Classifier

## How to Predict
```python
result = predict_spam("Your message here...")
# Returns True for Spam, False for Ham
