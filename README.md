# customer-review-sentiment

*Company*: CODTECH IT SOLUTIONS

*Name*: Chetan

*Inern Id*: CT04WM04

*Domain*: Machine Learning

*Duration*: 4 weeks

*Mentor*: Neela Santosh

This project implements sentiment analysis on the Amazon Fine Food Reviews dataset using TF-IDF vectorization and Logistic Regression.

## Overview
- **Dataset:** Amazon Fine Food Reviews ([Kaggle](https://www.kaggle.com/snap/amazon-fine-food-reviews)).
- **Preprocessing:** Removal of neutral reviews (Score = 3), basic text cleaning.
- **Vectorization:** TF-IDF (with stop words removed, max features set).
- **Model:** Logistic Regression with a maximum of 1000 iterations.
- **Evaluation:** Accuracy, precision, recall, F1-score, confusion matrix, and ROC curve.

## Usage
1. **Download Dataset:** Place `Reviews.csv` in the project folder.
2. **Install Dependencies:**  
   ```bash
   pip install -r requirements.txt

3. **Run Notebook:**  
   Launch Jupyter Notebook and execute `sentiment_analysis.ipynb`.

## Results Summary
- **Accuracy:** ~87%
- **Key Findings:**  
  - High recall for positive class (1.00)
  - Low recall for negative class (0.22)
