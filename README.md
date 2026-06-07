# Week4-DataScience-Tasks - Sales Forecasting & Business Analytics System

## Project Overview

This project focuses on analyzing historical sales data and building a machine learning model to forecast future sales. The project includes data preprocessing, exploratory data analysis, feature engineering, visualization, and predictive modeling.

## Objectives

- Clean and preprocess sales data
- Perform Exploratory Data Analysis (EDA)
- Generate business insights through visualizations
- Engineer time-based features from order dates
- Build a sales forecasting model using Linear Regression
- Evaluate model performance using regression metrics

## Dataset Features

The dataset contains:

- Order Date
- Ship Date
- Ship Mode
- Segment
- Country
- City
- State
- Region
- Category
- Sub-Category
- Product Name
- Sales

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Google Colab

## Data Preprocessing

- Removed missing values
- Removed duplicate records
- Converted date columns into datetime format
- Extracted Month, Year, and DayOfWeek features
- Encoded categorical variables

## Visualizations

- Monthly Sales Trend
- Yearly Sales Trend
- Category-wise Sales
- Sub-Category-wise Sales
- Region-wise Sales
- Segment-wise Sales
- Top 10 Products by Sales
- Sales Distribution
- Correlation Heatmap

## Machine Learning Model

Model Used:

- Linear Regression

Target Variable:

- Sales

Selected Features:

- Month
- Year
- Region
- Category
- Sub-Category
- Segment

## Model Evaluation

Evaluation Metrics:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The model achieved limited predictive performance due to the absence of additional business-related features such as quantity sold, discount information, and profit values.

## Business Insights

- Sales vary across different regions and customer segments.
- Certain product categories contribute significantly to overall revenue.
- Sales patterns change over time and can be analyzed using monthly and yearly trends.
- Top-performing products contribute a major share of sales.

## Conclusion

A complete Sales Forecasting and Business Analytics workflow was successfully implemented. The project demonstrates practical skills in data cleaning, exploratory data analysis, visualization, feature engineering, machine learning, and business insight generation.
