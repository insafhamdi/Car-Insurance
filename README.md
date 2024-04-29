
# On the Road Car Insurance Claim Prediction
## Overview
This repository contains the implementation of several machine learning models to predict whether a customer of "On the Road" car insurance will make a claim during the policy period. The project focuses on leveraging customer data to build models with high predictive accuracy, with the goal of simplifying and optimizing insurance claim predictions.

## Dataset
The dataset used in this project is stored in dataset. It includes various features related to the customer's profile such as age, driving experience, income level, and past driving records. The target variable is outcome, indicating whether a claim was made.

## Features
age: Age group of the client (categorical)
gender: Gender of the client
driving_experience: Years of driving experience
education: Education level
income: Income category
credit_score: Credit score between 0 and 1
vehicle_ownership, vehicle_year, vehicle_type: Details about the client’s vehicle
annual_mileage: Annual mileage
speeding_violations: Number of speeding violations
duis: Number of DUIs
past_accidents: Number of past accidents

## Models Implemented
Logistic Regression
Decision Tree
Random Forest

## Results
The models' performances are summarized as follows:

- Logistic Regression: Accuracy = 0.7307

- Decision Tree: Accuracy = 0.8302

- Random Forest: Best Accuracy = 0.8483

The Random Forest model, with feature selection and hyperparameter tuning, provided the best results.
