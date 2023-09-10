# GDP-Growth-Prediction-Analysis


## Overview
This repository contains Python code for an analysis of GDP growth and its relationship with various economic indicators. The analysis includes data preprocessing, visualization, statistical modeling, and future GDP growth predictions. The code utilizes libraries such as NumPy, Pandas, Matplotlib, Seaborn, SciPy, Statsmodels, and Scikit-Learn.

## Description
The code performs the following tasks:

Data Loading: Reads economic data from an Excel file (CA 1 Data set.xlsx) and displays the first few rows.

Data Exploration: Checks for duplicate years and missing values in the dataset. Descriptive statistics and histograms for numerical variables are visualized.

Time Series Visualization: Plots the trends of numerical variables over time to understand their patterns.

Correlation Analysis: Calculates and displays the correlation matrix heatmap to identify relationships between numerical variables.

Regression Analysis: Performs linear regression analysis to assess the relationship between GDP and selected economic indicators (BI and EI).

Predictive Modeling: Uses Scikit-Learn's Linear Regression model to predict GDP growth for the next 5 years (2024-2028) based on the selected economic indicators.

Visualization of Predictions: Plots the real vs. predicted GDP growth for the next 5 years.

## Usage
Ensure you have the required Python libraries installed. You can install them using pip or conda.

Replace the file path in the code with your own data file if necessary.

Run the code in your Python environment to perform the analysis and make predictions.

Explore the generated visualizations and regression summaries.


## Files
your_script.py: The Python script containing the analysis code.
CA 1 Data set.xlsx: The input data file (replace with your own dataset).
README.md: This README file providing an overview of the repository.
GDP Growth Prediction Analysis.pdf: Report wherre i did all discussiond related to macro economy


## Future Improvements
You can enhance this analysis by considering more advanced machine learning models and feature engineering techniques to improve prediction accuracy.