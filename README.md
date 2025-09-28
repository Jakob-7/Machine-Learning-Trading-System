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

