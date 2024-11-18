Overview:
This Python script predicts the next day's closing price for a given stock using a simple linear regression model. The model is trained on historical closing prices and then uses the most recent closing price to forecast the next day's price.

Features:

Data Source: The script fetches historical stock data from Yahoo Finance using the yfinance library.
Model: A simple Linear Regression model from sklearn is used for prediction.
Prediction: The model predicts the next day's closing price based on the last observed closing price.
Dependencies:
yfinance: Used to download stock price data from Yahoo Finance.
sklearn: Provides the LinearRegression model for training and predicting the stock price.
