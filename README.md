# Time-Series-Forecasting

This project aims to forecast gold prices using various time series analysis techniques. We utilize linear regression, naive forecasting, and Exponential Smoothing to predict future gold prices based on historical data. The project includes data loading, preprocessing, visualization, model building, and evaluation.

Table of Contents
- [Installation](#Installation)
- [Data](#Data)
- [Project Structure](#ProjectStructure)
- [Results](#Results)
- [Contact](#Contact)

Installation
To run this project locally, you will need to install the necessary dependencies. This can be done by running:
pip install pandas numpy seaborn matplotlib statsmodels scikit-learn
Data
The dataset used in this project consists of monthly gold prices. The data is loaded from a CSV file.
Project Structure
The project is organized as follows:

Time Series Forecasting.ipynb: The main Jupyter notebook containing all the code for data loading, preprocessing, visualization, and modeling.
gold_monthly_csv.csv: The dataset file containing monthly gold prices.
Results
The project implements and evaluates the following models:

Linear Regression: Fits a linear trend to the training data and evaluates it on the test data.
Naive Forecasting: Uses the last observed value as the forecast for all future values.
Exponential Smoothing: Applies Exponential Smoothing with additive trend and seasonality to fit the entire dataset and generate forecasts.
Key Metrics
MAPE: Mean Absolute Percentage Error is calculated to evaluate the accuracy of the models.
Visualizations
Time Series Plot: Visualizes the monthly gold prices.
Box Plots: Shows the distribution of gold prices by year and month.
Seasonal Plot: Illustrates the monthly seasonality of gold prices.
Forecast Plots: Compares actual prices with forecasts and includes confidence intervals.
Contact
If you have any questions or suggestions, feel free to contact me at hyderirfan09@gmail.com.

