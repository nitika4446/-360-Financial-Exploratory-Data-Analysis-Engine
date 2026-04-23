# 📈 360° Financial Exploratory Data Analysis Engine

A powerful **Streamlit-based financial analytics dashboard** that performs:

- Technical Analysis  
- Risk Analysis  
- Statistical EDA  
- AI Stock Scoring  
- Candlestick Chart Visualization  
- Downloadable Financial Reports  

This project allows users to upload stock market datasets (CSV/Excel) and generate actionable financial insights.

---

## 🚀 Features

### 1. Upload Financial Dataset
Upload:
- CSV files
- Excel files (.xlsx)

Required columns:
- Date
- Open
- High
- Low
- Close

Optional:
- Volume

---

## 📊 Technical Analysis

The project calculates:

- SMA (Simple Moving Average)
- EMA (Exponential Moving Average)
- RSI (Relative Strength Index)
- Bollinger Bands
- MACD Indicator

---

## ⚠ Risk Analysis

Generates:

- Annual Volatility
- Sharpe Ratio
- Maximum Drawdown

---

## 📈 Statistical EDA

- Dataset Summary Statistics
- Correlation Heatmap
- Trend Analysis

---

## 🤖 AI Stock Score

The application generates a stock score based on:

- Volatility
- Sharpe Ratio
- RSI
- Drawdown

Final output:
- Strong Buy Candidate
- Moderate Risk
- High Risk Stock

---

## 📉 Candlestick Chart

Interactive candlestick chart using Plotly.

---

## 📥 Download Report

Users can download the processed financial dataset.

---

# Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly

---

# Project Structure

```bash
financial-eda-engine/
│
├── app.py
├── requirements.txt
├── README.md
├── sample_data.csv
└── .gitignore
```

---

# Installation

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
cd financial-eda-engine
pip install -r requirements.txt
```

---

# Run Locally

```bash
streamlit run app.py
```

---

# Deployment

Deploy easily on Streamlit Cloud:

https://share.streamlit.io/

---

# Sample Dataset Format

| Date | Open | High | Low | Close | Volume |
|--------|--------|--------|--------|--------|---------|
| 2024-01-01 | 100 | 110 | 95 | 105 | 50000 |

---

# Future Improvements

- Real-time API integration using :contentReference[oaicite:0]{index=0}  
- News sentiment analysis  
- Portfolio optimization  
- ML-based stock prediction  
- LSTM forecasting  

---

# Author

Your Name

LinkedIn: Your LinkedIn Link  
GitHub: Your GitHub Profile Link
