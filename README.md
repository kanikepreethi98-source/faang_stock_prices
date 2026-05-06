# 📈 FAANG Stock Price Prediction with Technical Indicators

A complete deep learning project that predicts stock prices using **LSTM** and enhances analysis with **technical indicators (RSI, MACD)** and **candlestick visualization**.

---

## 🚀 Project Overview

This project focuses on predicting stock prices using historical data from FAANG companies and improving model performance using technical indicators.

It combines:

* 📊 Time Series Forecasting (LSTM)
* 📉 Technical Analysis (RSI, MACD)
* 🕯️ Candlestick Visualization

---

## 🏢 Dataset

FAANG stock dataset containing:

* Date
* Open
* High
* Low
* Close
* Volume
* Company Name

Companies included:

* Apple (AAPL)
* Amazon (AMZN)
* Google (GOOGL)
* Netflix (NFLX)
* Meta (META)

---

## 🧠 Model

* Long Short-Term Memory (LSTM)
* Multi-feature input:

  * Close Price
  * RSI
  * MACD
  * Signal Line

---

## 📊 Technical Indicators Used

### 🔹 Relative Strength Index (RSI)

* Measures momentum (0–100)
* Overbought (>70), Oversold (<30)

### 🔹 MACD (Moving Average Convergence Divergence)

* Trend-following indicator
* Uses EMA (12, 26) and Signal (9)

---

## 📉 Visualization

This project includes advanced visualization:

* 🕯️ Candlestick charts
* 📊 RSI panel
* 📈 MACD + Signal panel
* 📦 Volume tracking

---

## ⚙️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib
* mplfinance
* Scikit-learn
* TensorFlow / Keras

---

## 🔄 Workflow

1. Load FAANG dataset
2. Filter specific stock (e.g., AAPL)
3. Data preprocessing
4. Add RSI & MACD indicators
5. Normalize data
6. Create time-series sequences
7. Train LSTM model
8. Predict stock prices
9. Visualize with candlestick charts

---

## 📊 Results

* ✔️ Model captures stock trends effectively
* ✔️ Indicators improve learning
* ⚠️ Not fully accurate due to market volatility

---

## 📂 Project Structure

```
📁 stock-price-prediction
│── data/
│── notebooks/
│── model/
│── visualization/
│── app/ (optional Streamlit)
│── requirements.txt
│── README.md
```

---

## 🔮 Future Improvements

* Add GRU / Bidirectional LSTM
* Include more indicators (Bollinger Bands)
* Hyperparameter tuning
* Real-time stock prediction
* Deploy using Streamlit

---

## ⚠️ Disclaimer

This project is for educational purposes only.
Stock markets are influenced by external factors such as news, economic conditions, and sentiment.

---

## 📌 How to Run

```
git clone https://github.com/your-username/stock-prediction.git
cd stock-prediction
pip install -r requirements.txt
jupyter notebook
```

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---

## 📬 Contact

* LinkedIn: https://www.linkedin.com/in/kanike-preethi-061398334?utm_source=share_via&utm_content=profile&utm_medium=member_android
* GitHub: https://github.com/kanikepreethi98-source
