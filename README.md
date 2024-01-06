# Flight-Fare-Price-Prediction-✈️

Flight Price Prediction Model
Welcome to the Flight Price Prediction Model repository! This repository contains the code for predicting flight prices based on various features. The goal is to provide an accurate and reliable tool for pricing flights, aiding businesses in the travel industry.

📝 Features:
Airline:
Description: The airline providing the flight service.
Source:
Description: The departure city or airport.
Destination:
Description: The arrival city or airport.
Departure Time:
Description: The time of day when the flight departs.
Arrival Time:
Description: The time of day when the flight arrives.
Duration:
Description: The total duration of the flight in minutes.
Total Stops:
Description: The number of stops or layovers during the flight.
Aircraft Type:
Description: The type of aircraft used for the flight.
Date of Journey:
Description: The date when the flight departs.
Additional Features:
Description: Other features that may impact flight fare, including the provision of in-flight meals.
Flight Fare:
Description: The cost of the flight ticket.

Table of Contents 📑

Introduction
Dataset
Data Preprocessing
Exploratory Data Analysis
Feature Engineering
Model Selection
Model Evaluation
Optimization and Hyperparameter Tuning
Conclusion

Introduction
Flight prices can be influenced by a myriad of factors, and predicting them accurately is crucial for businesses in the travel industry. This repository presents a comprehensive approach to building a flight price prediction model using various machine learning algorithms.

Dataset
The dataset used for training and testing the model is sourced from Flight Price Dataset. It includes information such as date of journey, airline, source, destination, and additional details that can impact flight prices.

Data Preprocessing
Data preprocessing steps involve handling missing values, converting date columns to datetime, extracting relevant features, and encoding categorical variables. This ensures the dataset is ready for training machine learning models.

Exploratory Data Analysis
Exploratory Data Analysis (EDA) provides insights into the distribution of key variables, helping us understand trends and patterns in the data. Visualizations are included to showcase the distribution of airlines, sources, destinations, and other relevant features.

Feature Engineering
Feature engineering involves creating new features or transforming existing ones to enhance the predictive power of the model. Extracting information from date columns and encoding categorical variables are examples of feature engineering applied in this project.

Model Selection
Several machine learning models, including Linear Regression, Decision Tree, Random Forest, Extra Trees, Gradient Boosting, XGBoost, and LGBMRegressor, are considered. The Extra Trees model is identified as the optimal choice based on its performance metrics.

Model Evaluation
The selected model is evaluated using metrics such as Root Mean Squared Error (RMSE) and R-squared (R^2). The evaluation results demonstrate the model's accuracy in predicting flight prices.

Optimization and Hyperparameter Tuning
GridSearchCV is employed to fine-tune hyperparameters for the Gradient Boosting Regressor, further enhancing the model's performance.

Conclusion
The conclusion provides a business-oriented perspective on why the Extra Trees model is the preferred choice. It discusses the model's impact on decision-making, continuous improvement, and the overall benefits it brings to the business.






