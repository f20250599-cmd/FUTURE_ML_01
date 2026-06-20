# Sales Forecasting Project

## Overview
This project uses historical sales data to forecast future sales trends using Machine Learning techniques.

The dataset was cleaned, analyzed, and transformed into a time-series format before building a Linear Regression model for sales prediction.

## Objectives
- Analyze historical sales data
- Create time-based features
- Build a forecasting model
- Evaluate model performance
- Visualize sales trends and forecasts

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

## Dataset
- Sample Superstore Dataset
- 9,994 records
- 21 columns

## Project Workflow

### 1. Data Cleaning
- Loaded dataset
- Checked data types
- Verified missing values

### 2. Feature Engineering
- Converted Order Date to datetime format
- Created:
  - Year
  - Month
  - Quarter
  - Days since first observation

### 3. Sales Analysis
- Aggregated daily sales
- Visualized sales trends

### 4. Machine Learning Model
- Linear Regression
- Predicted future sales values

### 5. Model Evaluation
- Metric Used: Mean Absolute Error (MAE)
- MAE ≈ 1525.62

## Results
The model successfully generated future sales forecasts and provided insights into historical sales patterns.

## Repository Contents
- Sales_Forecasting.ipynb
- Sample - Superstore.csv
- ST.png (Sales Trend)
- SF.png (Sales Forecast)
- MS.png (Model Error)

