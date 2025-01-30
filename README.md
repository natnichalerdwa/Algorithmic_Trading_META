# Predictive Stock Analysis and Simulation – META

## Overview
This project focuses on analyzing and predicting META stock price trends using statistical modeling, machine learning, and technical analysis. The study incorporates GARCH and Kalman Filter models to estimate stock returns and price movements while leveraging technical indicators to enhance prediction accuracy. A trading strategy is developed based on multiple models, and its profitability is evaluated through backtesting.

## Objectives
* Apply the GARCH model to estimate daily log returns and Kalman Filter to estimate daily stock prices
* Use technical indicators (SMA, EMA, RSI, OBV) and candlestick patterns to interpret market conditions
* Construct a feature database using factors from sources like FRED, Fama-French, ADS, and stock market indicators
* Perform feature selection using Ridge regression, LASSO, Elastic Net, or decision-tree models (XGBoost, Random Forest)
* Design and train 3-6 quantitative models for predicting stock price/return
* Implement a benchmark study using GARCH/Kalman Filter
* Develop trading rules (buy-and-hold, long-short, or day trading) and evaluate Profit & Loss (P&L) from trading signals

## Methodology
1. Data Collection & Preprocessing
* Downloaded historical stock data using yfinance
* Cleaned and structured data using pandas and numpy
* Computed log returns and price lags for feature engineering

2. Statistical Modeling
* GARCH Model (statsmodels): Estimated volatility of returns
* Kalman Filter: Smoothed price estimation over time
* Kernel Density Estimation: Visualized return distribution

3. Technical Analysis
* Trend Indicators: SMA, EMA
* Momentum Indicators: RSI (overbought/oversold levels)
* Volume Analysis: OBV
* Candlestick Patterns: Doji, Hammer, Engulfing patterns

4. Feature Engineering & Selection
* Collected macroeconomic indicators from FRED, Fama-French, ADS
* Applied Ridge regression, LASSO, Elastic Net for feature selection
* Visualized feature importance using XGBoost and Random Forest

5. Predictive Modeling
* Implemented 3-6 models including Decision Trees (Random Forest, XGBoost), Regression-based models (LASSO, Ridge, Elastic Net)
* Time-series forecasting models
* Evaluated models using RMSE, precision, and recall

6. Trading Strategy & Backtesting
* Created buy/sell signals based on model predictions
* Compared Profit & Loss (P&L) of different trading strategies
* Benchmarked performance against a GARCH-based model

## Tools and Libraries
* pandas, numpy, matplotlib, seaborn (Data processing & visualization)
* yfinance, pandas_datareader (Stock data retrieval)
* statsmodels, scipy (GARCH modeling, statistical analysis)
* sklearn (Feature selection, regression models)
* xgboost, random_forest (Decision-tree modeling)
* scipy.optimize (Optimization and backtesting)

## Results
* Accurate return and price estimation using GARCH and Kalman Filter
* Feature selection improved model performance, reducing RMSE
* Profitable trading signals generated through technical indicators and predictive modeling
* Benchmark study confirmed the effectiveness of combining statistical models and technical analysis for stock trading

## Team members
* Lerdwanawattana, Natnicha
* Liu, Hu
* Nayak, Shrikrishna
* Patil, Srushti Sunil
* Ryan, Aqeel

## References
* Data Sources: Yahoo Finance, FRED, Fama-French, ADS
* Steve Nison’s Japanese Candlestick Charting Techniques
