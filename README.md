# House Price Forecasting using LINEAR_REGRESSION
Project Overview:
The goal of this project is to build a predictive model that estimates house prices based on various features such as the number of bedrooms, bathrooms, square footage, and year built.

Dataset:
The dataset used is kc_house_data.csv, which contains sales data for houses in King County, including Seattle. It includes houses sold between May 2014 and May 2015.

Features Used:
bedrooms, bathrooms, sqft_living, sqft_lot, floors, condition, grade, sqft_above, sqft_basement, yr_built, yr_renovated, lat, long, sqft_living15, sqft_lot15.
Requirements:
To run this notebook, you need the following Python libraries installed:

pandas
numpy
scikit-learn
matplotlib
seaborn
Workflow
Data Loading: Reading the dataset using pandas.
Data Exploration: Checking for missing values and summarizing statistical properties.
Feature Selection: Dropping non-numeric or less relevant columns for the initial regression model.
Data Splitting: Dividing the data into training (80%) and testing (20%) sets.
Model Training: Fitting a LinearRegression model from scikit-learn.
Evaluation: Assessing performance using R-squared and Mean Squared Error (MSE).
Visualization: Creating a regression plot to compare actual vs. predicted prices.
Results:
R-squared Score: 0.65
Mean Squared Error: 52,258,480,929.86
The model explains approximately 65% of the variance in house prices based on the selected features.

Visualization:
The notebook includes a regression plot that visualizes the relationship between the actual prices and the prices predicted by the model.
