# machinelearningXstocks

# 📊 Stock Market Price Prediction using Linear Regression

This project demonstrates how to use **Machine Learning (Linear Regression)** to predict the next day's closing price of a stock using historical price data. The dataset is automatically fetched using the **Yahoo Finance API** (`yfinance`), and the model is trained using the `scikit-learn` library.

---

## 📌 Features

- ✅ Fetch historical stock data via Yahoo Finance
- ✅ Train a linear regression model on past prices
- ✅ Predict the **next day's closing price**
- ✅ Visualize actual vs predicted closing prices

---

## 🧠 How It Works

This project assumes a simple relationship between a stock’s current closing price and its next closing price. It:

1. Downloads stock data (default: `RELIANCE.NS`) using `yfinance`
2. Uses the current day’s closing price as a feature
3. Uses the **next day’s closing price** as the target
4. Trains a **Linear Regression** model
5. Predicts future price and plots results

---

## 🚀 Getting Started

### ✅ Prerequisites

- Python 3.8+
- pip

### 📥 Installation

Clone the repository:
```bash
git clone https://github.com/yourusername/stock-price-prediction.git
cd stock-price-prediction
