# ML Trader - AI Price Predictor

A Machine Learning-powered stock price prediction app for Indian NSE/BSE markets.

## 🚀 Quick Start

```powershell
cd "c:\POC\capital markets\MLTrader"
npm install
npm run dev
```

Open **http://localhost:3001** in your browser.

## ✨ Features

### ML Models Used
- **LSTM** (Long Short-Term Memory) - Deep learning for time series
- **Random Forest** - Ensemble decision trees
- **XGBoost** - Gradient boosting algorithm

### Features Analyzed
- **Technical Indicators**: RSI, MACD, EMA, Bollinger Bands, ADX, Supertrend
- **Sentiment Features**: News NLP, Social media buzz, Analyst ratings, Insider activity
- **Volume Features**: Volume ratio, OBV, MFI, Delivery %

### Output
- Top 5 BUY recommendations with target prices
- Top 5 SELL/AVOID recommendations
- Holding periods: 1 Month, 3 Months, 6 Months
- Confidence scores based on model consensus

## 📊 How It Works

1. Models analyze 50+ features for each stock
2. Each model (LSTM, RF, XGBoost) generates independent predictions
3. Ensemble combines predictions with weighted voting
4. Confidence score = % of models agreeing on direction

## ⚠️ Disclaimer

This is for educational purposes only. Not financial advice.
