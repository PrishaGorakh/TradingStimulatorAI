# TradingStimulatorAI
This project is a Trading Simulator that leverages a linear regression model to predict stock closing prices and generate trading signals (Buy, Sell, Hold). The simulator is designed to help users understand stock price movements and make informed trading decisions based on historical data.

# Features:
Data Processing: Load and preprocess historical stock data. Linear Regression Model: Train a linear regression model using features like Open, Low, High, Volume, and date components. Price Prediction: Predict the next day's closing price based on the trained model. Trading Signals: Generate buy, sell, or hold signals based on predicted prices. User-Friendly Output: Display results in a clear and concise format for easy analysis.

# Prerequisites
Python 3.x Required libraries: pandas, numpy, scikit-learn, and matplotlib.

# Dataset
The dataset contains a total of 25,161 rows, each row representing the stock market data for a specific company on a given date. The information collected through web scraping from www.nasdaq.com includes the stock prices and trading volumes for the companies listed, such as Apple, Starbucks, Microsoft, Cisco Systems, Qualcomm, Meta, Amazon.com, Tesla, Advanced Micro Devices, and Netflix.

https://www.kaggle.com/datasets/khushipitroda/stock-market-historical-data-of-top-10-companies
