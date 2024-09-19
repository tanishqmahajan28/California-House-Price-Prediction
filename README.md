# California House Price Prediction Project

This project focuses on predicting California house prices using machine learning models. The dataset provides various features like house location, size, number of rooms, and proximity to amenities, which are used to build predictive models. The goal is to accurately predict house prices, offering valuable insights for real estate applications.

## Table of Contents

- [Overview](#overview)
- [Who Will Find This Helpful](#who-will-find-this-helpful)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Feature Engineering](#feature-engineering)
- [Models Implemented](#models-implemented)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Conclusion and Future Work](#conclusion-and-future-work)

## Overview

This project aims to predict house prices in California using various machine learning algorithms. The dataset contains features such as house size, number of bedrooms, proximity to the ocean, and more. The project demonstrates the complete workflow from data preprocessing, model training, and evaluation to prediction.

## Who Will Find This Helpful

This project will be helpful for:

- **Data Scientists and Analysts:** Looking to practice predictive modeling for real estate data.
- **Real Estate Professionals:** Interested in understanding how machine learning can help estimate property values.
- **Students and Researchers:** Learning about regression problems and data preprocessing techniques.
- **Developers:** Integrating price prediction models into real estate applications.

## Dataset

The dataset used for this project contains house features from various locations in California, including details such as number of rooms, lot size, and geographical location. You can find the dataset from [here](https://www.kaggle.com/datasets/shibumohapatra/house-price).

## Data Preprocessing

1. **Data Cleaning:** Handled missing values and removed outliers.
2. **Feature Scaling:** Standardized numeric features to bring them to a common range.
3. **Encoding Categorical Variables:** Applied encoding techniques for non-numeric features.

## Exploratory Data Analysis

Visualizations were created to understand the distribution of features and relationships between them. Key insights about feature importance and correlations guided the feature selection process.

## Feature Engineering

The following features were derived for better model performance:

- **Price per Room:** Calculated as the house price divided by the number of rooms.
- **Proximity to Amenities:** New features created based on the proximity of houses to key amenities.
- **Interaction Terms:** Combined existing features to capture complex relationships.

## Models Implemented

Several regression models were implemented to predict house prices, including:

- **Linear Regression**
- **Random Forest Regressor**
- **Decision Tree Regressor**
- **Support Vector Regressor**

## Model Evaluation

The models were evaluated using metrics such as:

- **Mean Absolute Error (MAE):** Average of absolute errors between predicted and actual prices.
- **Mean Squared Error (MSE):** Average of the squared differences between predicted and actual prices.
- **R-squared:** A measure of how well the model explains the variance in the target variable.

## Results

- **Best Performing Model:** Linear Regressor, with the lowest Overfitting and highest R-squared value.
- **Comparison:** Linear Regressor performed better than other models in terms of prediction.

## Conclusion and Future Work

The California house price prediction project demonstrates how machine learning models can predict house prices effectively. Future work could focus on incorporating more detailed geographical data and improving feature selection.

