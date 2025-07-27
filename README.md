


<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/b69d84ff-019e-462f-aae7-5f1345b04156" /> 
 
# AlgoTrade Project - Intelligent Forecasting Engine For Stock Trading
 
### Our goal: Build a smart, end-to-end pipeline that automates data collection, feature extraction, and multi-model forecasting—wrapped in an intuitive agent interface.

In this project, we built an intelligent forecasting engine that predicts stock price movements using multiple 
time-series models within an agent-based interface. The system supports natural language queries for all tickers available via Yahoo Finance (yfinance), enabling intuitive access to advanced forecasts. I focused on optimizing a Long Short-Term Memory (LSTM) neural network, a powerful deep learning model well-suited for capturing temporal dependencies in financial data, while my teammates developed ARIMA/SARIMAX and XGBoost models to explore diverse approaches to financial time series forecasting.

# Project Overview
  * Built an end-to-end algotrading system for forecasting stock prices.
  * Automatically: Fetches data from “Yahoo Finance” & enriches with features and correlations.
  * Generates forecasts using multiple ML models.
  * Wrapped in a chat-like agent interface for easy user interaction.
  * Supports custom input: stock symbol, forecast horizon, and model choice.
  * Designed for modularity, scalability, and real-world trading use.

<img width="1046" height="352" alt="image" src="https://github.com/user-attachments/assets/9f5db39f-9886-441a-8a18-986727ba2588" />

# Results
**Use case** -  predicting the next 30 days of stock prices of AAPL stock by using a 60-day window of past data to predict the next day.
<img width="800" height="800" alt="image" src="https://github.com/user-attachments/assets/2975fff3-eae2-45e1-98d1-ad682ccdeaf4" />

<img width="300" height="285" alt="image" src="https://github.com/user-attachments/assets/a2db99ce-69a1-4e3d-ae10-eace7b1cd456" />

# Conclusion
  * Our system supports all tickers available in Yahoo Finance, enabling wide-scale forecasting coverage.
  * All models demonstrated strong performance in forecasting stock prices.
  * LSTM achieved the highest R² (0.9930), excelling at learning sequential patterns.
  * Classical models like ARIMA and SARIMAX provided reliable results with low RMSE.


