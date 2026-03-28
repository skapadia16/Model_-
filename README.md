# Model_-
TCS Stock Price Prediction
Overview

This Python project predicts the next-day closing price of TCS (Tata Consultancy Services) shares using Linear Regression and Polynomial Regression.
The project allows you to:

Use historical TCS stock data (CSV file).
Choose between Linear or Polynomial regression.
Input a hypothetical last price to predict the next-day price.
Visualize actual vs predicted prices in a chart.
Features
Simple and interactive – anyone can run and input data.
Supports Polynomial Regression to capture trends better than linear models.
CSV-based – works without requiring Python 3.7+ or yfinance.
Outputs a chart and predicted next-day price.
Requirements
Python 3.6+

Required Python libraries:

pip install pandas numpy matplotlib scikit-learn
Optional: yfinance (Python 3.7+), if you want automatic data download.
Usage
Download or prepare a CSV file of TCS historical prices with columns:
Date, Open, High, Low, Close, Volume

Run the Python script:

python tcs_prediction.py
Follow the prompts:
Type 'csv' to load your CSV file.
Enter the path to your CSV file.
Choose model type: 'linear' or 'polynomial'.
If polynomial, enter the degree (2 or 3 recommended).
Enter a hypothetical last closing price to predict the next-day price.
View output:
Predicted next-day price printed on the console.
Chart showing actual vs predicted prices.
Example
Type 'yahoo' to download TCS data or 'csv' to load CSV file: csv
Enter CSV file path: TCS_history.csv
Enter model type ('linear' or 'polynomial'): polynomial
Enter polynomial degree (e.g., 2 or 3): 3
Enter hypothetical last price to predict next-day: 4500

Predicted next-day price based on input 4500: 4523.45

The chart will display the predicted vs actual closing prices over time.

Notes
Predictions are based on historical trends. They do not guarantee actual stock performance.
Polynomial regression may overfit if the degree is too high.
For real-time data, upgrade Python to 3.7+ and use yfinance.
License

This project is free to use for educational and personal purposes.
