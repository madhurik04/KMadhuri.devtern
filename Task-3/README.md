# Task - 3

# Heart Disease Prediction

## Overview

This project aims to predict the presence of heart disease based on various medical features. The dataset includes information such as age, sex, and various medical indicators. The goal is to develop a predictive model to assist in early diagnosis.

## Dataset

- **File:** [HeartDiseasePrediction](https://www.kaggle.com/datasets/rishidamarla/heart-disease-prediction)
- **Features:**
  - `Age`: Age of the patient
  - `Sex`: Gender of the patient
  - `Chest pain type`: Type of chest pain experienced
  - `BP`: Blood pressure
  - `Cholesterol`: Cholesterol level
  - `FBS over 120`: Fasting blood sugar
  - `EKG results`: Electrocardiographic results
  - `Max HR`: Maximum heart rate achieved
  - `Exercise angina`: Exercise-induced angina
  - `ST depression`: Depression induced by exercise relative to rest
  - `Slope of ST`: Slope of the peak exercise ST segment
  - `Number of vessels fluro`: Number of major vessels colored by fluoroscopy
  - `Thallium`: Thallium stress test result
  - `Heart Disease`: Presence or absence of heart disease (target variable)

## Steps

1. **Data Preparation**
   - Data Loading
   - Data Cleaning: Handled missing values and encoded categorical variables
   - Feature Selection
   - Data Splitting

2. **Model Building**
   - Used algorithms including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.

3. **Model Evaluation**
   - Evaluated models using accuracy, precision, recall, F1-score, and confusion matrix.

4. **Best Model**
   - The Gradient Boosting Classifier achieved the best performance based on evaluation metrics.

## Files

- `heart_disease.csv`: Dataset
- `heart_disease_prediction.py`: Script for data processing, feature selection, model training, and evaluation
- `best_model.pkl`: Saved best model (Gradient Boosting Classifier)

## Usage

Run the script `heart_disease_prediction.py` to execute the data processing, model training, and evaluation. The best model will be saved as `best_model.pkl`.

