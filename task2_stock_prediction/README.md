# 📈 Task 2: Stock Price Prediction using Machine Learning

## Project Overview
This project predicts the next day's closing price of a stock using historical market data. The model uses machine learning techniques to analyze patterns in stock price movements.

---

## Objective
To build a regression model that can predict future stock prices based on historical data such as Open, High, Low, and Volume.

---

## Dataset
- Source: Yahoo Finance (via `yfinance` library)
- Stock used: Apple Inc. (AAPL)
- Time range: 2020 - 2024

---

## Approach

1. Data Collection using Yahoo Finance API
2. Data Preprocessing and Feature Selection
3. Splitting dataset into training and testing sets
4. Model Training using Linear Regression
5. Model Evaluation using MAE and RMSE
6. Visualization of Actual vs Predicted Prices

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yFinance

---

## Machine Learning Model

- Model Used: Linear Regression
- Input Features: Open, High, Low, Volume
- Target Variable: Close Price (Next Day Prediction)

---

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## Results

- The model successfully learned patterns in stock price movements.
- Predictions closely followed actual price trends.
- However, slight deviations exist due to market volatility and randomness.

---

## Conclusion

This project demonstrates a complete end-to-end machine learning workflow for financial prediction, including data collection, preprocessing, model building, evaluation, and visualization.

---

## How to Run

1. Install dependencies: