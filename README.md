# Stock Market Prediction

This repository contains code for predicting stock market trends using various techniques and analyzing stock data of different companies. The code performs data analysis, visualization, and model evaluation to predict the stock market.

## Getting Started

### Prerequisites
Make sure you have the following libraries installed:
- numpy
- pandas
- seaborn
- matplotlib
- missingno
- plotly
- sklearn
- keras
- statsmodels

### Usage
Open the Jupyter notebook `stock_market_prediction.ipynb` and run each cell to execute the code step-by-step.

### Data
The code considers data from eight companies: Twitter, Netflix, SNP, Amazon, Tesla, Apple, Microsoft, and Walmart. The data files for each company should be placed in the specified location. The code reads the data, performs analysis and visualization on individual and combined data.
Here is the link to the data 
- https://www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs

### Data Analysis and Visualization
The code includes various data analysis and visualization techniques to gain insights into the stock market trends. Here are some of the visualizations performed:

- Candlestick chart comparison for Twitter, Netflix, Apple, and Walmart
- Bar chart comparison of closing values for Microsoft, Netflix, Apple, and Tesla
- Bar chart comparison of volume for Microsoft, Netflix, Apple, and Tesla
- Daily return percentage comparison between Apple and Tesla
- Pairplot of close values between all considered companies
- Jointplot to analyze the correlation between different companies' data returns
- Time series analysis of stock market using line graphs and bar graphs
- Heatmap to visualize the correlation between data features

### Model Evaluation
The code includes various models for stock market prediction, such as linear regression, decision tree regression, LSTM, and ARIMA. The models are evaluated using metrics like mean squared error and mean absolute error.
