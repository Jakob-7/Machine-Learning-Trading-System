# Machine Learning Trading System

This project builds a market-neutral trading strategy using machine learning (XGBoost). It predicts next-day asset directions using technical features and constructs a long/short portfolio with risk-based weighting.

---

## Strategy Overview

- Asset Universe: Forex pairs, commodities, and ETFs
- Features: Momentum, volatility, RSI, z-score
- Model: XGBoost Classifier (with hyperparameter tuning)
- Signal: Long if predicted prob > 0.6, Short if < 0.4
- Position Sizing: Inverse volatility weighting
- Portfolio: Market-neutral (long = short)
- Evaluation: Sharpe Ratio, Drawdown, CAGR, Equity Curve

---

## 📁 Files

| File | Description |
|------|-------------|
| `ML_Trading_System_v2_Classification.ipynb` | Full notebook: data → features → model → backtest |
| `requirements.txt` | Python libraries used |
| `.gitignore` | Prevents large/unnecessary files from being uploaded |

---

## How to Run

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
