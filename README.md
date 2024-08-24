Dr. Reddy's Stock Price Prediction Using LSTM
This repository contains Python code for predicting the stock prices of Dr. Reddy's Laboratories using a Long Short-Term Memory (LSTM) neural network. The stock price data is directly sourced from Yahoo Finance, making this a practical example of financial time series forecasting.

Key Features:
Data Source: Stock price data for Dr. Reddy's Laboratories is fetched directly from Yahoo Finance.
Data Preprocessing: The code handles preprocessing tasks like normalization, data splitting (into training and testing sets), and reshaping the data to fit the LSTM model's requirements.
LSTM Model Architecture: Built using TensorFlow/Keras, the model consists of several LSTM layers followed by Dense layers, designed to effectively capture and predict the stock price trends.
Training: The model is trained on historical data, using Mean Squared Error (MSE) as the loss function to reduce prediction errors.
Prediction: Post-training, the model predicts future stock prices for Dr. Reddy's, with a visual comparison between predicted and actual prices.
Evaluation: The model's performance is assessed using Root Mean Squared Error (RMSE) to gauge prediction accuracy.
Requirements:
Python 3.x
TensorFlow/Keras
NumPy
Pandas
Matplotlib
