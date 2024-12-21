# Project_IronKaggle

Project Overview

This project analyzes housing prices in King County, using a dataset spanning from May 2014 to May 2015. The goal is to clean and preprocess the data, perform exploratory data analysis (EDA), engineer new features, and utilize machine learning models to predict house prices accurately.

Objectives
	•	Clean and preprocess raw data to ensure accuracy and consistency.
	•	Perform exploratory data analysis to understand patterns and correlations.
	•	Engineer meaningful features to enhance model performance where applicable.
	•	Build regression models to predict house prices:
	•	Baseline Model: Linear Regression
	•	Optimized Model: XGBoost
	•	Evaluate and compare model performance using metrics like R², RMSE, MSE, and MAE.

Dataset
	•	Source: Kaggle, thanks to Mina Sameh55.
	•	Key Features:
	•	price: The target variable (house prices).
	•	sqft_living: Square footage of the living area.
	•	bedrooms: Number of bedrooms.
	•	bathrooms: Number of bathrooms.
	•	zipcode, latitude, longitude: Geographical location data.

Tools and Libraries
	•	Languages: Python
	•	Libraries:
	•	Data Analysis: pandas, numpy
	•	Visualization: matplotlib, seaborn, plotly
	•	Machine Learning: scikit-learn, XGBoost

Steps

1. Data Cleaning
	•	Handled missing values and dropped irrelevant columns (id).
	•	Converted date into a year_month format for time-based analysis.

2. Exploratory Data Analysis (EDA)
	•	Visualized correlations and distributions of key features.
	•	Created custom price segments to analyze price ranges and their frequency.

3. Feature Engineering
	•	Added a price_per_sqft feature to normalize house prices.
	•	Segmented data to understand price distributions and count comparisons.

4. Modeling
	•	Built a Linear Regression model as a baseline.
	•	Optimized predictions using XGBoost, applying hyperparameter tuning to improve performance.

5. Evaluation
	•	Compared models using the following metrics:
	•	R²: Coefficient of determination
	•	RMSE: Root Mean Squared Error
	•	MSE: Mean Squared Error
	•	MAE: Mean Absolute Error
	•	XGBoost outperformed other models by effectively capturing non-linear relationships in the data.

Results
	•	Best Model: XGBoost
	•	Key Metrics:
	•	R²: o.8842
	•	RMSE: 129315.01
	•	MSE: 16722373855.3125
	•	MAE: 68314.9065

