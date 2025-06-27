# Citi Stock Price Forecasting (2019–2024)

## Project Overview
This project forecasts weekly closing prices of Citi (Ticker: C) stock using two time series models: ARIMA and Prophet. 
The goal is to compare their forecasting performance and understand how they handle trend, seasonality, and noise in financial time series data.

## Tools & Libraries
- Python
- yfinance
- pandas, matplotlib, seaborn
- statsmodels (ARIMA)
- prophet (Facebook Prophet)

## Project Structure
- data/               # CSV stock price data
- notebooks/          # Jupyter notebooks for each step
- visuals/            # Forecast plots, EDA charts
- utils/              # Optional: scripts like data fetchers

## Data Source
- Yahoo Finance - Citi (C) - https://finance.yahoo.com/quote/C/
