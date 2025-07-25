
# 📈 AI/ML Internship Tasks: Stock Price Prediction with `yfinance`

Welcome to my AI/ML internship project repository! This repository contains simple, practical experiments using Python to predict stock prices using **historical market data** retrieved from Yahoo Finance.

---

## 🚀 **Task Objective**

The goal of this task is to explore how different machine learning models can predict the **next day's closing price** for a selected stock using only its historical daily market data.  
This helps build practical skills in:
- Data collection with `yfinance`
- Feature engineering for time series prediction
- Training simple regression models
- Evaluating and visualizing predictions

---

## 📚 **Dataset Used**

- **Source:** [Yahoo Finance](https://finance.yahoo.com/)
- **Retrieval:** Using the `yfinance` Python library
- **Stocks selected:**  
  - **Apple (AAPL)**: 2015–2024  
  - **Tesla (TSLA)**: 2015–2024  
- **Features used:** Open, High, Low, Volume  
- **Target:** Next day's Close price

---

## 🤖 **Models Applied**

1. **Random Forest Regressor**
   - Applied on **Apple (AAPL)** stock data
   - Used to test the performance of an ensemble method on stock price prediction

2. **Linear Regression**
   - Applied on **Tesla (TSLA)** stock data
   - Used to test a simple baseline regression model

---

## 📊 **Key Results & Findings**

- The **Random Forest model** performed reasonably on Apple stock data but showed that even complex ensemble models can struggle with volatile, unpredictable stock trends.
- Interestingly, the **simple Linear Regression model** performed **comparatively better** on Tesla stock data than Random Forest did on Apple.  
- This highlights that, for certain stocks and with limited features, simpler models can sometimes generalize better than complex ones — especially when the input data does not capture deeper market signals.

---

## ✅ **Next Steps**

- Experiment with additional features such as moving averages, technical indicators, or lag variables.
- Try advanced models like LSTM for sequence prediction.
- Explore hyperparameter tuning to improve the Random Forest model.

---


