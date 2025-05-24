# Stock_Market_
Stock Market Analysis & Apple Stock Price Prediction with LSTM
This project analyzes historical stock market data of major tech companies — Apple (AAPL), Amazon (AMZN), Google (GOOG), and Microsoft (MSFT) — using Python libraries such as yfinance, pandas, matplotlib, and seaborn. Additionally, it implements a Long Short-Term Memory (LSTM) model using Keras to predict Apple Inc.'s future stock closing prices.

Inspired by: Fares Sayah's LSTM Stock Prediction project



 Project Objectives
This notebook aims to:

Retrieve and visualize stock data using yfinance

Perform basic statistical and time-series analysis

Examine daily returns, risk, and correlations between stocks

Calculate and visualize moving averages

Predict the closing stock price of Apple Inc. using an LSTM neural network

🛠 Technologies Used
Python 3.x

Jupyter Notebook / Google Colab

Libraries:

yfinance

pandas

numpy

matplotlib

seaborn

scikit-learn

keras / tensorflow



 Data Source
Stock price data is fetched using the Yahoo Finance API through the yfinance Python library. The dataset includes daily price and volume data from January 2024 to December 2024 for:

Apple (AAPL)

Google (GOOG)

Microsoft (MSFT)

Amazon (AMZN)

For LSTM, we use Apple stock data from 2012 to the present.

 Exploratory Data Analysis
The following techniques were used to understand stock behavior:

Line plots of closing prices and trading volume

Moving averages (10, 20, 50 days)

Daily return analysis using histograms and percentage changes

Correlation matrices and heatmaps

Risk vs. Return scatter plot

Pair plots and KDE plots to analyze relationships

 Stock Price Prediction with LSTM
We build a deep learning LSTM model to predict Apple’s future closing prices:

Data is scaled using MinMaxScaler

We use a 60-day look-back window

The model includes:

2 LSTM layers

1 Dense layer with 25 units

1 Dense output layer

Trained on 95% of the dataset; tested on 5%.
