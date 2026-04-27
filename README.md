# Sentiment Analysis with Machine Learning and MLflow

This project implements an end-to-end sentiment analysis pipeline for classifying text as positive or negative.

## Project Overview

The goal of this project is to compare different NLP approaches and machine learning models for sentiment classification and analyze their performance.

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
- Comparison with LLM-based classification via API

## Results

- Best model: Logistic Regression + TF-IDF
- Accuracy: 0.86
- F1-score: 0.86

## Hyperparameter Tuning (MLflow)

<img width="1775" height="969" alt="image" src="https://github.com/user-attachments/assets/2485da5d-5bf8-4e22-8eca-68eabe84afa3" />


## Tech Stack

- Python
- Scikit-learn
- MLflow
- SHAP
- Pandas, NumPy

## Kaggle source

https://www.kaggle.com/datasets/bittlingmayer/amazonreviews
