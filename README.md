# Sentiment Analysis with Machine Learning and MLflow

This project implements an end-to-end sentiment analysis pipeline for classifying text as positive or negative.

## Project Overview

The goal of this project is to compare different NLP approaches and machine learning models for sentiment classification and analyze their performance.

## 🚀 Project Highlights

- End-to-end NLP pipeline
- MLflow experiment tracking
- Hyperparameter tuning (GridSearchCV)
- SHAP model interpretability
- Comparison: ML vs LLM

## Features

- Text preprocessing (cleaning, stopword removal, lemmatization)
- Vectorization methods: TF-IDF and Bag-of-Words
- Model comparison:
  - Logistic Regression
  - SVM
  - Naive Bayes
  - XGBoost
- Hyperparameter tuning using GridSearchCV
- Experiment tracking with MLflow
- Model interpretability using SHAP
- Comparison with LLM-based classification via API (Accuracy: 0.90)

## Results

- Best model: Logistic Regression + TF-IDF
- Accuracy: 0.86
- F1-score: 0.86

## Hyperparameter Tuning (MLflow)

<img width="1775" height="969" alt="image" src="https://github.com/user-attachments/assets/2485da5d-5bf8-4e22-8eca-68eabe84afa3" />

## Model Interpretability (SHAP)

To better understand model predictions, SHAP (SHapley Additive exPlanations) was used.

### Feature Importance

<img width="1001" height="1144" alt="image" src="https://github.com/user-attachments/assets/bc161ee6-105c-4cc6-ac8a-ce345592a2fe" />


This plot shows the most important features influencing the model predictions.

### Force Plot

<img width="1323" height="300" alt="image" src="https://github.com/user-attachments/assets/8fa7e0c8-7095-4efa-9e72-39565932b355" />

The SHAP force plot provides a local explanation of an individual prediction by showing how each feature contributes to the final output.

## Tech Stack

- Python
- Scikit-learn
- MLflow
- SHAP
- Pandas, NumPy

## Kaggle source

https://www.kaggle.com/datasets/bittlingmayer/amazonreviews
