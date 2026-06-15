# Heart-Disease-Prediction-using-Logistic-Regression
# Project Overview

This project focuses on predicting the likelihood of heart disease using Machine Learning. A Logistic Regression model was developed to classify whether a patient is at risk of heart disease based on various medical attributes.
Early prediction of heart disease can help healthcare professionals provide timely treatment and improve patient outcomes.

# Problem Statement

Heart disease is one of the leading causes of death worldwide. Identifying high-risk patients at an early stage is crucial for effective medical intervention.
The objective of this project is to build a classification model that can predict the presence of heart disease using patient health data.

# Dataset Information
The dataset contains medical information collected from patients and includes several health-related attributes used to predict heart disease.

# Features
The dataset contains attributes such as:
Age
Sex
cp
trestbps	
chol	
fbs	
restecg	
thalach	
exang	
oldpeak	
slope	
ca	
thal	
target

# Target Variable
Variable	   Description
target	     Heart Disease Prediction 

# Data Exploration
Before model training, the dataset was analyzed to:
Examine column information
Check data types
Identify missing values
Analyze unique values
Understand the target variable distribution

This step helps ensure data quality and suitability for machine learning.

# Data Preprocessing

The following preprocessing steps were performed:
Separated input features and target variable.
Split the dataset into training and testing sets.
Applied feature scaling using StandardScaler.
Prepared the data for Logistic Regression training.

Feature scaling was used to improve model performance and convergence.

# Machine Learning Model
# Logistic Regression
Logistic Regression is a supervised machine learning algorithm used for binary classification problems.
It estimates the probability of a patient having heart disease and classifies the outcome into:

Positive Heart Disease Case
Negative Heart Disease Case 

# Model Training Strategy
The dataset was divided into:
67% Training Data
33% Testing Data
The model was trained on the training dataset and evaluated on unseen test data.

# Evaluation Metrics
The model performance was evaluated using:

# Accuracy Score
Measures the percentage of correctly classified observations.

# Precision Score
Measures how many positive predictions were actually correct.

# Confusion Matrix
Provides a detailed breakdown of:

True Positives
True Negatives
False Positives
False Negatives
This helps evaluate classification performance beyond overall accuracy.

# Technologies Used
Python
Pandas
Seaborn
Scikit-learn
Jupyter Notebook
