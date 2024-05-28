# Web Traffic Time Series Forecasting
This project focuses on forecasting the daily number of views for various Wikipedia articles using historical web traffic data from July 2015 to November 2017. The goal is to predict future traffic accurately, aiding in server capacity planning and content strategy adjustments.

Project Overview
The Web Traffic Time Series Forecasting project utilizes several statistical and machine learning models to predict page views. This repository contains the code, data processing scripts, and documentation for models including ARIMA, LSTM, and XGBoost.

Datasets
The datasets include approximately 145k time series from different Wikipedia articles, provided in the following files:

train_1.csv.zip: Training data from July 1, 2015, to December 31, 2016.
train_2.csv.zip: Additional training data extending up to September 1, 2017.
Models Used
ARIMA: Autoregressive Integrated Moving Average model, suitable for time series data that is stationary or made stationary through transformations.
LSTM: Long Short-Term Memory networks, a type of recurrent neural network suitable for sequence prediction problems.
XGBoost: Gradient boosting framework that uses decision trees and ensemble techniques.
Prophet: Forecasting tool designed for handling daily observational data that displays patterns on different time scales.
Features
Data preprocessing and cleaning scripts.
Implementation of multiple time series forecasting models.
Evaluation of models using metrics like MSE (Mean Squared Error) and SMAPE (Symmetric Mean Absolute Percentage Error).
Visualization of predictions and model diagnostics.
