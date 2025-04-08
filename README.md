# Stock-Prediction-using-LSTM

Overview

This project uses an LSTM-based deep learning model to predict stock prices from historical market data, improving accuracy over traditional forecasting methods.

Features

LSTM model for sequential stock data processing

Data preprocessing including normalization

Hyperparameter tuning for optimization

Evaluation using Mean Squared Error (MSE)

Dataset

The dataset includes:

Date (Trading date)

Open/Close Price (Stock prices)

High/Low Price (Daily range)

Volume (Shares traded)

Methodology

Data Preprocessing: Cleaning and structuring data

Model Design: LSTM architecture for trend prediction

Training & Optimization: Tuning epochs, batch size, optimizer

Evaluation: Performance analysis using MSE

Results

LSTM outperforms traditional methods like Moving Averages & ARIMA

Lower MSE, better adaptability to market changes

Installation

git clone https://github.com/034adarsh/Stock-Price-Prediction-Using-LSTM.git
cd Stock-Price-Prediction-Using-LSTM
pip install -r requirements.txt
python lstm_model.py

Future Enhancements

Hybrid Models: Combining LSTM with CNN/GRU

Sentiment Analysis: Using financial news & social media
