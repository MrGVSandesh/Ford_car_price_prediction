# Ford_car_price_prediction

This project focuses on predicting car prices using machine learning techniques. The notebook demonstrates the complete data science workflow including data exploration, preprocessing, feature engineering, and model building using Linear Regression.

1. Project Overview

The objective of this project is to analyze the Ford car dataset and build a predictive model to estimate car prices based on various features such as model type, mileage, fuel type, engine size, and year of manufacture.

2. Dataset Description

The dataset contains information about Ford cars with the following key attributes:
..>Model
..>Year
..>Transmission type
..>Mileage
..>Fuel type
..>Tax
..>MPG (Miles Per Gallon)
..>Engine Size
..>Price (Target Variable)

3. Exploratory Data Analysis (EDA)

Exploratory analysis was performed to understand data distribution and relationships between variables.
..>Examined dataset shape, structure, and summary statistics
..>Checked for missing values and data consistency
..>Visualized price distribution using histograms
..>Generated correlation heatmap to understand relationships
..>Used boxplots to detect outliers and understand feature impact
..>Scatter plots were used to analyze mileage vs price trends

4. Data Cleaning & Preprocessing

Data preparation steps were performed to ensure quality input for model training.
..>Verified and handled missing values
..>Separeted features and target variable
..>Converted categorical features into numerical format
..>Ensured consistent data types for modeling

5. Feature Engineering & Encoding

To make the data suitable for machine learning:
One-Hot Encoding was applied to categorical variables:
..>model
..>transmission
..>fuelType
Label Encoding was also demonstrated for categorical transformation.
Feature scaling was applied using StandardScaler to normalize numerical features:
..>year
..>mileage
..>tax
..>mpg
..>engineSize

6. Model Building — Linear Regression

A Linear Regression model was built to predict car prices.
..>Dataset split into training and testing sets
..>Model trained using training data
..>Predictions generated on test data

7. Model Evaluation

Model performance was evaluated using statistical metrics:
..>R² Score — measures model accuracy
..>Adjusted R² Score — accounts for number of predictors used
Error metrics used:
..>Mean Absolute Error (MAE)

Mean Squared Error (MSE)

These metrics help evaluate how well the model predicts car prices.
