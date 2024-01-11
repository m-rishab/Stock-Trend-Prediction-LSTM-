# Stock Trend Prediction using LSTM

Predicting stock prices is a challenging task due to the dynamic and complex nature of the stock market. Traditional machine learning tools have been utilized for stock market prediction, but with the increasing volume of data, deep learning models like Long Short-Term Memory (LSTM) networks have proven to be advantageous in terms of accuracy and speed.

## Project Overview

This project focuses on predicting stock trends using LSTM, a type of recurrent neural network (RNN) suitable for handling time-series data. The goal is to provide investors with more accurate forecasts, aiding in decision-making for stock investments.

## Flow Chart

![LSTM](https://github.com/m-rishab/Stock-Trend-Prediction-LSTM-/assets/113618652/876dfa80-d26e-4eb8-bab6-ccf3104f2e7d)

## Steps to Implement LSTM Model

1. **Data Collection:**
   - Utilize `yfinance` to dynamically fetch historical stock data based on start and end dates. `yfinance` is a convenient Python library that provides access to Yahoo Finance data.

2. **Data Preprocessing:**
   - Clean and preprocess the data, handling missing values and scaling if necessary.

3. **Feature Engineering:**
   - Extract relevant features for LSTM input.

4. **Model Training:**
   - Fit the LSTM model on the preprocessed data.

5. **Prediction:**
   - Use the trained model to predict future stock prices.


## Website

Explore the live version of the project on [[project website link](https://stock-prediction-f01l.onrender.com/)].

## Steps to Run the Project

## Steps to Run the Project

1. Input any stock ticker.
2. Click on predict.

To run the code locally, follow these steps:

```bash
streamlit run app.py
