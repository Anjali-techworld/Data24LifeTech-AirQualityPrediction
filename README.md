# Data24LifeTech-AirQualityPrediction
The primary goal is to analyze and monitor air quality levels across various regions using the AirNow real-time dataset. This can support environmental policy, public health recommendations, or forecasting models.
This project focuses on predicting PM2.5 Air Quality Index (AQI) levels using real-time environmental monitoring data from the AirNow dataset.
The target of this project is PM2.5 AQI(sorting),compared to other AQI values its have less missing values.
Feature selection was performed using a Random Forest Regressor to identify the most relevant predictors in the dataset. Based on importance scores, the top 10 features were selected for building and optimizing the final regression model.
The goal is to develop a machine learning model capable of accurately forecasting air pollution severity to aid in public health awareness and environmental management. After thorough data preprocessing and exploratory data analysis (EDA), various regression models were evaluated. 
Linear Regression emerged as the best-performing model based on its interpretability and performance metrics.
A custom pipeline was built using the top 10 most relevant features, and the model achieved an R² score of 0.80 on test data, indicating strong predictive power.
However, the model showed reduced accuracy on unseen data, highlighting challenges in generalization and the importance of consistent preprocessing. 
The project emphasizes the potential of machine learning to forecast AQI trends and supports future integration into environmental monitoring systems.
Further improvements are recommended through advanced modeling, feature engineering, and real-time deployment to enhance predictive reliability and impact.

