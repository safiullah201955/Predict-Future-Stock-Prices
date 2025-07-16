# Predict-Future-Stock-Prices

This repository contains a simple machine learning pipeline to predict the closing price of Tesla (TSLA) stock using historical price data. The project demonstrates how to fetch stock data, train a model, and evaluate its performance.

# Task Objective

The project aims to predict Tesla’s daily closing stock price using machine learning. It fetches historical data, trains a Linear Regression model, evaluates performance, and visualizes actual versus predicted prices to assess predictive accuracy.

# Dataset Used

Stock data for Tesla (TSLA) was collected via Yahoo Finance using the yfinance API.
It includes Open, High, Low, Adjusted Close, Volume, and Close prices for the period between January 2023 and July 2025.

# Models Applied

A Linear Regression model from scikit-learn was applied. It was trained on historical price features and evaluated using R² and RMSE metrics. The model’s ability to generalize on unseen data was tested with an 80-20 train-test split.

# Key Results and Findings

The model showed high accuracy on training data of (R² ≈ 0.99).
