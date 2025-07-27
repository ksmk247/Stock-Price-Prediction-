# Stock-Price-Prediction-

This project analyzes and predicts Google stock prices using historical data obtained from yfinance. The process involves:

Data Acquisition and Exploration: Downloading historical stock data, performing exploratory data analysis (EDA) to understand its characteristics, checking for missing values and duplicates, and visualizing distributions and correlations of different stock attributes (Open, High, Low, Close, Volume, Dividends, Stock Splits).
Data Preprocessing: Scaling the data using MinMaxScaler to normalize the values between -1 and 1.
Sequence Generation: Creating sequences of data for training the LSTM model, using a defined sequence length (11 in this case).
Data Splitting: Splitting the data into training, validation, and testing sets.
LSTM Model Development and Training: Building a Sequential LSTM model using TensorFlow/Keras, compiling it with the Adam optimizer and Mean Squared Error loss, and training it on the prepared data.
Model Evaluation: Evaluating the trained LSTM model on the test data and visualizing the actual vs. predicted stock prices.
Model Architecture Visualization: Displaying the architecture of the trained LSTM model.
Candlestick Charting: Generating candlestick charts of the predicted stock prices using mplfinance and plotly.graph_objects.
Time Series Analysis with SMAs: Calculating and visualizing Simple Moving Averages (SMAs) for different time windows (10, 20, and 50 days) to observe trends.
Daily Return Analysis: Calculating and plotting the daily percentage change in the closing price to analyze volatility.
PyTorch Implementation of LSTM: Implementing and training separate LSTM models using PyTorch with different input features (10-day SMA, 20-day SMA, and both), comparing their performance on the test set, and generating predictions for the next 10 days.
This project provides a comprehensive approach to analyzing and predicting stock prices using historical data and deep learning techniques.
