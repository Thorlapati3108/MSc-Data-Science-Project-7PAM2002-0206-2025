# MSc-Data-Science-Project-7PAM2002-0206-2025
A Time Series Forecasting Study of Gold Prices Using Machine Learning and Deep Learning Techniques

## 📌 Overview
This project analyses and forecasts **Gold Prices (GC=F)** using machine learning and deep learning models on historical data from **2010 to 2025**. 

Models implemented:
- Random Forest
- XGBoost
- LSTM (Deep Learning)
- Tuned LSTM

---

## 📊 Dataset
- Source: Yahoo Finance (`yfinance`)
- Period: 2010 – 2025
- Features: Open, High, Low, Close, Volume

---

## ⚙️ Workflow
1. Data Extraction & Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering (returns, volatility, lag features)  
4. Model Training  
5. Forecasting (next 60 days)

---

## 🤖 Models

- **Random Forest & XGBoost**
  - Poor performance  
  - Failed to capture strong upward trend  

- **LSTM**
  - Best model  
  - Captures time dependencies effectively  

- **Tuned LSTM**
  - Slightly worse due to overfitting  

---

## 📈 Performance (Key Insight)

- LSTM → **R² ≈ 0.98 (Best)**
- Tuned LSTM → Slight drop in performance  
- Tree-based models → Negative R² (poor)

---

## 🔮 Forecast
- LSTM used for **60-day future prediction**
- Shows continuation of upward trend  

---

## 🚀 Run on Google Colab
python
!pip install yfinance pandas numpy matplotlib seaborn scikit-learn tensorflow

- Upload notebook → Run all cells → View results
