# Intelligent Agent for Predicting Commodity Price Changes

## Overview
This project presents an intelligent agent designed to predict changes in the prices of various commodities, including crude oil, natural gas, and gold. The agent utilizes historical price data and machine learning algorithms, including Facebook Prophet, ARIMA, K-Nearest Neighbors (KNN), Linear Regression, and Random Forest Regression, to make accurate predictions.

## Data Cleaning Process
The data cleaning process involves:
- Handling missing values in the dataset.
- Parsing dates and extracting features like year, month, and day.
- Removing redundant columns and formatting data types for analysis.

## Visualization
Visualizations are utilized to explore the data and understand trends, patterns, and correlations. Key visualizations include:
- Time series plots for each commodity to visualize price trends over time.
- Histograms and box plots to analyze the distribution and variability of prices.
- Correlation matrices to identify relationships between different commodities and features.

## Algorithms Used
The following machine learning algorithms and forecasting models are employed in this project:
- **Facebook Prophet**: A forecasting tool developed by Facebook for time series data forecasting. It is capable of capturing trends, seasonality, and holiday effects.
- **ARIMA (AutoRegressive Integrated Moving Average)**: A widely used time series forecasting method that models the next step in the sequence as a linear function of the observations and residual errors at prior time steps.
- **K-Nearest Neighbors (KNN)**: Utilized for its simplicity and effectiveness in classification and regression tasks.
- **Linear Regression**: Employed to model the relationship between independent variables and commodity prices.
- **Random Forest Regression**: Utilized for its ability to handle nonlinear relationships and capture complex patterns in the data.

## Contents
- `crude-oil-price.csv`: CSV file containing historical crude oil price data.
- `natural-gas-price.csv`: CSV file containing historical natural gas price data.
- `gold-price-data.csv`: CSV file containing historical gold price data.
- `crude_oil_price_prediction.ipynb`: Jupyter Notebook containing code for predicting crude oil prices.
- `natural_gas_price_prediction.ipynb`: Jupyter Notebook containing code for predicting natural gas prices.
- `gold_price_prediction.ipynb`: Jupyter Notebook containing code for predicting gold prices.
- `README.md`: This file providing an overview of the repository.


## Dependencies
- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- fbprophet
- statsmodels

## Contributors
- [Akshaya Narayana](https://github.com/contributor_username)
- [Sai Charan Thummalapudi](https://github.com/your_username)

