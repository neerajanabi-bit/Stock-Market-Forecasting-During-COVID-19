# 📈 Stock Market Forecasting During COVID-19 Using Machine Learning and Deep Learning

## Overview

This project presents a machine learning and deep learning framework for forecasting the directional movement of the Indian stock market during the COVID-19 pandemic.

The study evaluates multiple predictive models across different COVID-19 market regimes and compares their performance using both classification metrics and trading strategy evaluation.

---

## Objectives

- Forecast stock market direction during COVID-19.
- Compare Machine Learning and Deep Learning models.
- Evaluate performance under different pandemic market regimes.
- Interpret model predictions using SHAP analysis.
- Assess trading strategy performance against Buy-and-Hold.
- Develop an interactive Streamlit dashboard.

---

## Models Implemented

- Logistic Regression
- XGBoost
- Long Short-Term Memory (LSTM)

---

## Features Used

### Technical Indicators

- RSI
- MACD
- SMA
- EMA
- Bollinger Bands
- Momentum
- Volatility

### COVID-19 Features

- Pandemic Regimes
- Lockdown Period
- Recovery Phase
- Wave Indicators

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Sharpe Ratio
- Maximum Drawdown
- Annual Return

---

## Trading Strategy

The project evaluates the practical usefulness of the forecasting models using:

- Rolling Window Strategy
- Buy-and-Hold Benchmark
- Transaction Cost Analysis

---

## Explainability

Model predictions are interpreted using:

- SHAP Summary Plot
- SHAP Feature Importance

---

## Dashboard

A Streamlit dashboard was developed for:

- Market Analysis
- Model Comparison
- Prediction Interface
- Trading Strategy Evaluation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- TensorFlow / Keras
- SHAP
- Matplotlib
- Seaborn
- Streamlit
- SQLite

---

## Project Structure

```
├── dashboard/
├── data/
├── models/
├── notebooks/
├── report/
├── images/
├── README.md
```

---

## Results

- XGBoost demonstrated robust predictive performance across volatile market regimes.
- SHAP analysis improved model interpretability.
- The rolling-window strategy showed improved trading performance compared to passive investment during selected market phases.

---

## Future Work

- Transformer-based forecasting models
- Real-time stock prediction
- Live API integration
- Portfolio optimization
- Cloud deployment

---

## Author

Neerajana Biswas

M.A. Financial Economics
Summer Internship, IDEAS-TIH,ISI Kolkata
