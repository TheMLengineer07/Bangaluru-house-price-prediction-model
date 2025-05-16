# Bangaluru house price prediction_model

# Overview

* Predicting house prices is a crucial task in real estate, helping buyers and sellers make informed decisions. This project leverages machine learning 
  techniques to predict house prices in Bengaluru, India, based on various features.

# Objective

  The goal of this project is to develop a predictive model that estimates house prices using historical data, considering factors like location, size, 
  number of bedrooms, and amenities.

* Performing data exploration to understand trends.
* Creating relevant features such as price per square foot.
* Removing outliers to improve prediction accuracy
* Optimization model perforamce using Grid Dearch CV
* Using different algorithms to comapre their accuracy respectively
  
# Data Source
* https://github.com/TheMLengineer07/Bangaluru-house-price-prediction-model/blob/main/bengaluru_house_prices.csv

# Data Preprocessing

 The dataset undersoes preprocessing steps,including
* Feature Addition: Creating Price per square foot as an informative feature
* Oulier Detection & Removal: detect outlier and remove them which creat noise in the model
* Categorical Feature Engineering: Encoding location based features for better predictions

# Methodology

# Exploratory Data Analysis(EDA)

* Understanding the distribution of price, square footage, and bedroom counts.
* Visualizing price trends across locations.
* Identifying extreme values that act as outliers.

# Feature Engineering
* Creating price per square foot for improved accuracy.
* Handling categorical variables using one-hot encoding.

# Model Selection
* we use different algorithms like-Linear Regression,Lasso and Decision Tree to compare their accuracy
* Creating price per square foot for improved accuracy.
* Handling categorical variables using one-hot encoding.

# Implementation

# Tools and Technology
* Programming Language:Python
* Libraries Used:Pandas,numpy,sklearn.matplotlib,Searborn

#Results and Analysis

# Model Performance
* Accuracy: Evaluated using R-squared score and find Linear Regression model with 84% has the maximun accuracy.
* Error Metrics: Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
* Feature Importance: Understanding how different factors affect price.

# Conclusion and Future Scope
#  Summary
* The project successfully predicts house prices using Linear Regression,Decision Tree Regressor and Lasso
* Removing outliers and feature engineering improves accuracy.
* Hyperparameter tuning using Grid Search CV optimizes model performance.
