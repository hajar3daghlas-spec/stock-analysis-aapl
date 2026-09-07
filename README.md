# Stock Price Analysis & Simple Forecasting

A statistical exploration of AAPL stock price behavior (2022–2024), covering 
exploratory data analysis, volatility, and basic forecasting techniques.

## What this project does
- Pulls historical stock data using `yfinance`
- Analyzes daily returns and their statistical distribution
- Computes moving averages (20-day, 50-day) to identify trends
- Measures rolling volatility to study risk over time
- Fits a simple linear regression as a naive forecasting baseline

## Key findings
- Daily returns show fat tails — extreme moves are more common than a normal 
  distribution predicts
- Volatility spikes align closely with sharp price declines
- A linear trend captures the general direction but misses short-term dynamics, 
  highlighting why naive models are insufficient for real forecasting

## Tools used
Python, pandas, numpy, matplotlib, yfinance, scikit-learn

## Disclaimer
This project is for educational purposes only and is not financial advice or 
a trading strategy.
