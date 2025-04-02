# B-S-A
# Bike Sharing Demand Prediction

## Problem Statement:
The goal of this project is to predict the demand for shared bikes using a linear regression model. The dataset includes various features such as weather conditions, temperature, humidity, and others. This prediction will help the bike-sharing company plan for future demand.

## Dataset:
- The dataset contains the daily number of bikes rented, along with weather conditions and other features.
- `cnt`: Total number of bikes rented.
- `season`: The season of the year.
- `weathersit`: Weather situation.
- `temp`, `humidity`, etc.

## Approach:
- Data preprocessing was performed to convert categorical variables into dummy variables.
- A multiple linear regression model was built using `scikit-learn`.
- The model was evaluated using R-squared score and residual analysis.

## Results:
- R-squared: 0.85
- The model has a good fit and can be used for predicting future bike demands.
