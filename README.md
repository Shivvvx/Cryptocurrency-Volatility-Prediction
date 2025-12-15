# Cryptocurrency Volatility Prediction

This project focuses on predicting cryptocurrency price volatility using historical market data and machine learning techniques.

## Problem Statement
Cryptocurrency markets are highly volatile. Accurate volatility prediction helps traders and investors
manage risk and make informed trading decisions.

## Dataset
The dataset contains historical data of multiple cryptocurrencies with the following features:
- Open price
- High price
- Low price
- Close price
- Market Capitalization
- Date
- Cryptocurrency Name

## Methodology
- Data cleaning and preprocessing
- Feature engineering (moving averages, price range, log market cap)
- Volatility calculation using rolling standard deviation of log returns
- Model training using Random Forest Regression
- Model evaluation using Mean Absolute Error (MAE)

## Model Used
- Random Forest Regressor

## Result
The trained model achieved a Mean Absolute Error (MAE) of approximately **0.015**, indicating good
predictive performance.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub

## How to Run
1. Open the Jupyter Notebook (`crypto_volatility_prediction.ipynb`)
2. Upload the dataset (`dataset.xlsx`) if required
3. Run all cells sequentially

## Author
Shivam Kumar
