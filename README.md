# Financial Forecasting and Analysis Pipeline
This project is a complete pipeline for financial data analysis and predictive modeling, built in Python and designed to run in Google Colab. It combines real-time stock data with synthetic datasets to demonstrate a variety of forecasting and classification techniques.
## Project Highlight
### <li>Stock Data Acquisition</li>
Uses the Yahoo Finance API (yfinance) to fetch historical stock prices. Includes feature engineering such as log returns, moving averages, and volati
### <li>Stock Price Prediction</li>
Implements both Linear Regression and ARIMA models to analyze trends and forecast future stock prices.

### <li>Credit Risk Modeling</li>
Uses a synthetic dataset to build a Logistic Regression model that predicts loan defaults based on income, loan amount, and credit score.

### <li>Revenue Forecasting</li>
Simulates future business revenue over time using a linear regression approach on synthetic data.

### <li>Exploratory Data Analysis (EDA)</li>
Includes pairplots and a correlation heatmap to visualize relationships between key financial features.

### <li>Stochastic Modeling</li>
Demonstrates Geometric Brownian Motion (GBM) to simulate stock price behavior under random market conditions.

# Notes
<li>Credit risk and revenue forecasting use randomly generated (synthetic) data</li>

<li>The ARIMA model may generate warnings related to date indexing.</li>

<li>This project is best run in a Jupyter environment such as Google Colab.</li>


