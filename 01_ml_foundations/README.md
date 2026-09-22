# Lesson 01: Machine Learning Foundations and First Model

## Overview

This lesson introduces the basic concepts of Machine Learning and demonstrates the complete workflow of building a first classification model using the Iris dataset.

## Learning Objectives

After completing this lesson, I learned how to:

- Understand Artificial Intelligence, Machine Learning, and Deep Learning
- Identify features, targets, and samples
- Differentiate classification and regression
- Understand supervised and unsupervised learning
- Load and explore a dataset
- Use Pandas DataFrames
- Split data into training and testing sets
- Train a Logistic Regression model
- Make predictions
- Evaluate a classification model
- Predict new unseen samples

## Topics Covered

### 1. AI, Machine Learning, and Deep Learning

- Artificial Intelligence
- Machine Learning
- Deep Learning

### 2. Basic Machine Learning Concepts

- Feature
- Target
- Sample

### 3. Types of Machine Learning Problems

- Classification
- Regression
- Supervised Learning
- Unsupervised Learning

### 4. Dataset

The Scikit-learn Iris dataset was used in this lesson.

The dataset contains:

- 150 samples
- 4 input features
- 3 flower classes

### Features

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

### Target Classes

- Setosa
- Versicolor
- Virginica

## Tools and Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Kaggle Notebook

## Machine Learning Model

The first model used in this lesson is:

**Logistic Regression**

## Basic Machine Learning Workflow

Dataset  
↓  
Features (X) + Target (y)  
↓  
Train-Test Split  
↓  
X_train, X_test, y_train, y_test  
↓  
Create Model  
↓  
model.fit(X_train, y_train)  
↓  
Trained Model  
↓  
model.predict(X_test)  
↓  
y_pred  
↓  
Compare y_pred with y_test  
↓  
Model Evaluation  
↓  
Accuracy, Confusion Matrix, Classification Report

## Model Evaluation

The model was evaluated using:

- Accuracy
- Confusion Matrix
- Precision
- Recall
- F1-score
- Classification Report

## New Sample Prediction

The trained model was also used to predict new flower samples using:

`model.predict()`

Class probabilities were observed using:

`model.predict_proba()`

## Key Concepts Learned

- `X` represents input features.
- `y` represents the target.
- `fit()` trains a machine learning model.
- `predict()` generates predictions.
- `predict_proba()` provides class probabilities.
- Training data is used for learning.
- Testing data is used for evaluating unseen-data performance.
- Model evaluation is necessary before trusting predictions.

## Practice

The lesson includes exercises on:

- Dataset inspection
- Train-test splitting
- Logistic Regression
- Accuracy calculation
- Confusion Matrix
- New sample prediction
- Prediction probabilities
- Incorrect prediction analysis
