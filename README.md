# 📈 Stock Price Prediction

A beginner-friendly Machine Learning project that predicts stock prices using historical stock market data and **Linear Regression**.

## 🚀 Project Overview

This project uses historical stock data to:

* Collect stock market data
* Clean and preprocess the data
* Visualize stock price trends
* Train a Linear Regression model
* Predict stock prices
* Compare actual and predicted prices

The project is created using **Python, Pandas, NumPy, Matplotlib, Scikit-learn, and Yahoo Finance API**.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* yfinance
* Linear Regression

## 📊 Dataset

The project can use historical stock market data from **Yahoo Finance** through the `yfinance` Python library.

You do **not need to manually download a dataset** if your code uses `yfinance`.

Example:

```python
import yfinance as yf

data = yf.download("AAPL", start="2020-01-01", end="2025-01-01")
```


## ▶️ How to Run

Run the Python program:

```bash
python stock_prediction.py
```


## 📈 Output

The project generates visualizations showing:

* Historical stock price trends
* Actual vs predicted prices

