# Wine Quality Prediction using Machine Learning

This project applies regression models to predict wine quality based on physicochemical properties.
It focuses on preprocessing, scaling, model comparison, and evaluation.

## Dataset
- Wine Quality (Red Wine) dataset
- Target variable: Quality score (regression task)
- Features include acidity, alcohol content, sulphates, pH, etc.

## Data Preparation
- Train-test split with fixed random state
- Feature scaling using StandardScaler
- Separation of features and target variable

## Models Implemented
- Random Forest Regressor
- Gradient Boosting Regressor

These models were chosen to compare ensemble-based regression approaches.

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

The comparison highlights how different models capture nonlinear relationships in the data.

## Observations
- Ensemble models outperform simple linear assumptions
- Scaling impacts model stability
- Performance varies depending on bias–variance trade-off

## Learning Outcome
This project strengthened understanding of:
- Regression vs classification problems
- Model evaluation for continuous targets
- Practical trade-offs in model selection

## Purpose
The goal of this project is to build intuition for **regression workflows** and model behavior rather than achieving maximum leaderboard performance.
