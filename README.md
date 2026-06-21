# Sales Forecasting Project

# Overview

This project uses historical sales data to forecast future sales trends using Machine Learning techniques.

The dataset was cleaned, analyzed, and transformed into a time-series format before building a forecasting model for sales prediction.

# Objectives

* Analyze historical sales data
* Create time-based features
* Build a forecasting model
* Evaluate model performance
* Visualize sales trends and forecasts

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

# Dataset

* Sample Superstore Dataset
* 9,994 Records
* 21 Columns

# Project Workflow

## 1. Data Cleaning

* Loaded dataset
* Checked data types
* Verified missing values

## 2. Feature Engineering

* Converted Order Date to datetime format
* Created:
    * Year
    * Month
    * Quarter
    * Days Since First Observation

## 3. Sales Analysis

* Aggregated daily sales
* Visualized historical sales trends

## 4. Machine Learning Model

* Linear Regression
* Predicted future sales values

## 5. Model Evaluation

* Metric Used: Mean Absolute Error (MAE)
* Evaluated forecasting accuracy

# Results

The model successfully generated future sales forecasts and provided insights into historical sales patterns and trends.

# Repository Contents

* Sales_Forecasting.ipynb
* Sample-Superstore.csv
* ST.png (Sales Trend Visualization)
* SF.png (Sales Forecast Visualization)
* MS.png (Model Evaluation/Error Visualization)

# How to Run

1. Clone the repository
2. Install required libraries
```bash
pip install pandas numpy matplotlib scikit-learn
```

3. Open the Jupyter Notebook
```bash
jupyter notebook Sales_Forecasting.ipynb
```
4. Run all cells to reproduce the results


### This project was completed as part of the Future Interns Machine Learning Internship Program.

# Author

Roshini Varanat Rajesh

BE Mathematics & Computing
