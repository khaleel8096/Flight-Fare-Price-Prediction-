# Flight-Fare-Price-Prediction-✈️

# Flight Price Prediction Model

Welcome to the Flight Price Prediction Model repository! This project aims to predict flight prices based on various features, offering an accurate and reliable tool for pricing flights and assisting businesses in the travel industry.

## Features

- **Airline:** The airline providing the flight service.
- **Source:** The departure city or airport.
- **Destination:** The arrival city or airport.
- **Departure Time:** The time of day when the flight departs.
- **Arrival Time:** The time of day when the flight arrives.
- **Duration:** The total duration of the flight in minutes.
- **Total Stops:** The number of stops or layovers during the flight.
- **Aircraft Type:** The type of aircraft used for the flight.
- **Date of Journey:** The date when the flight departs.
- **Additional Features:** Other features that may impact flight fare, including the provision of in-flight meals.
- **Flight Fare:** The cost of the flight ticket.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Model Selection](#model-selection)
- [Model Evaluation](#model-evaluation)
- [Optimization and Hyperparameter Tuning](#optimization-and-hyperparameter-tuning)
- [Conclusion](#conclusion)

## Introduction

Flight prices can be influenced by various factors, and predicting them accurately is crucial for businesses in the travel industry. This repository presents a comprehensive approach to building a flight price prediction model using various machine learning algorithms.

## Dataset

The dataset used for training and testing the model is sourced from the [Flight Price Dataset](#). It includes information such as date of journey, airline, source, destination, and additional details that can impact flight prices.

## Data Preprocessing

Data preprocessing steps involve handling missing values, converting date columns to datetime, extracting relevant features, and encoding categorical variables. This ensures the dataset is ready for training machine learning models.

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) provides insights into the distribution of key variables, helping us understand trends and patterns in the data. Visualizations are included to showcase the distribution of airlines, sources, destinations, and other relevant features.

## Feature Engineering

Feature engineering involves creating new features or transforming existing ones to enhance the predictive power of the model. Extracting information from date columns and encoding categorical variables are examples of feature engineering applied in this project.

## Model Selection

Several machine learning models, including Linear Regression, Decision Tree, Random Forest, Extra Trees, Gradient Boosting, XGBoost, and LGBMRegressor, are considered. The Extra Trees model is identified as the optimal choice based on its performance metrics.

## Model Evaluation

The selected model is evaluated using metrics such as Root Mean Squared Error (RMSE) and R-squared (R^2). The evaluation results demonstrate the model's accuracy in predicting flight prices.

## Optimization and Hyperparameter Tuning

GridSearchCV is employed to fine-tune hyperparameters for the Gradient Boosting Regressor, further enhancing the model's performance.

## Conclusion

The conclusion provides a business-oriented perspective on why the Extra Trees model is the preferred choice. It discusses the model's impact on decision-making, continuous improvement, and the overall benefits it brings.







