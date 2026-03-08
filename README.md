# Real Estate Price Prediction (Machine Learning Project)

## Project Overview

This project analyzes housing data from King County, USA, to predict house prices using machine learning models.
The goal is to understand how property features such as square footage, number of bedrooms, and location influence market price.

## Dataset

The dataset contains residential house sales from **King County (Seattle area)** between **May 2014 and May 2015**.

Key features include:

* Square footage of living space
* Number of bedrooms
* Number of bathrooms
* Floors
* Waterfront view
* Geographic location
* Overall house grade

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Machine Learning Models

The following models were implemented:

1. Linear Regression
2. Multiple Linear Regression
3. Ridge Regression
4. Polynomial Ridge Regression

## Results

| Model                       | R² Score |
| --------------------------- | -------- |
| Linear Regression           | ~0.49    |
| Ridge Regression            | 0.66     |
| Polynomial Ridge Regression | **0.70** |

Polynomial regression improved performance by capturing nonlinear relationships between housing features and price.

## Key Insights

* Larger living area strongly increases house price.
* Waterfront properties have significantly higher prices.
* Polynomial features improved model performance.

## Future Improvements

* Feature engineering
* Hyperparameter tuning
* Gradient boosting models
* Interactive dashboards

Aishi Dutta
B.Tech Computer Science Engineering
