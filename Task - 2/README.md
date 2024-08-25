# Task 2

# Spam Detection

## Overview

This project focuses on classifying emails as spam or ham (non-spam) using machine learning techniques. The dataset includes features derived from email text, and the goal is to build an effective spam filter.

## Dataset

- **File:** `spam-mails-dataset.csv`
- **Features:**
  - `Unnamed: 0`: Index
  - `label`: Spam or ham (target variable)
  - `text`: The email content
  - `label_num`: Numerical representation of the label (0 for ham, 1 for spam)

## Steps

1. **Data Preparation**
   - Data Loading
   - Data Cleaning: Removed special symbols and irrelevant information
   - Text Preprocessing: Tokenization, removing stopwords, and vectorization

2. **Feature Extraction**
   - Text features were extracted using techniques such as TF-IDF vectorization.

3. **Model Building**
   - Used different algorithms including Logistic Regression, Naive Bayes, and Support Vector Machine (SVM).

4. **Model Evaluation**
   - Evaluated models using metrics such as accuracy, precision, recall, and F1-score.

## Files

- `spam-mails-dataset.csv`: Dataset
- `spam_detection.py`: Script for data processing, feature extraction, model training, and evaluation

## Usage

Run the script `spam_detection.py` to perform data processing, train the models, and evaluate their performance.

