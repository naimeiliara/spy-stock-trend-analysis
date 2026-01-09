# SPY Stock Trend & Risk Analysis

This project analyzes historical price data of the S&P 500 ETF (SPY) to explore long-term trends, volatility, downside risk, and simple forecasting approaches that can support investment decision-making.

## Objective
To assess whether historical price patterns and risk metrics can provide meaningful insights into short-term market behavior while highlighting the limitations of predictive approaches.

## Data Source
- Historical daily price data for SPY (Yahoo Finance)
- Time period: 2015–Present

## Tools Used
- Python (Pandas, NumPy, Matplotlib)
- Jupyter Notebook
- Yahoo Finance (`yfinance`)

## Key Analyses
- Long-term price trend analysis
- Daily return and volatility assessment
- Rolling 30-day annualized volatility
- Maximum drawdown analysis
- Moving average trend indicators (50-day and 200-day)
- Simple rolling-average forecast (baseline reference)

## Key Findings
- SPY exhibits a strong long-term upward trend, interrupted by sharp but temporary drawdowns during periods of market stress.
- The maximum drawdown over the period was approximately **-33.7%**, highlighting the magnitude of downside risk investors may face.
- Volatility is time-varying and increases significantly during market shocks.
- Simple forecasting methods provide contextual trend guidance but are not suitable for precise market timing.

## Limitations
- The analysis relies on historical price data and does not account for future macroeconomic conditions.
- Forecasting methods are intentionally simple and should not be interpreted as investment advice.
- Transaction costs, dividends, and taxes are excluded.

## Project Structure

## Author
Nenyoratah Teveli

*This project was completed as part of a personal data analytics portfolio.*
