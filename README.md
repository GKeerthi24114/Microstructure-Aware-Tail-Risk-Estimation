# 📈 Microstructure-Aware Intraday Tail Risk Estimation for NSE NIFTY 50

An AI-driven financial risk estimation framework that combines **GARCH volatility forecasting**, **Extreme Value Theory (EVT)**, and **Generalized Pareto Distribution (GPD)** to estimate extreme downside market risk for the NSE NIFTY 50. The framework performs dynamic Value-at-Risk (VaR), Conditional Value-at-Risk (CVaR), heavy-tail modeling, and statistical validation using intraday market data.

---

## 📌 Project Overview

Traditional Gaussian-based financial risk models often underestimate extreme market losses because they fail to capture heavy tails, volatility clustering, skewness, and excess kurtosis.

This project introduces a **microstructure-aware preprocessing framework** that removes overnight and weekend market distortions before applying advanced statistical risk models.

The system dynamically estimates market risk using GARCH and EVT, providing more realistic financial risk assessment during volatile market conditions.

---

## ✨ Features

- 📈 Hourly NSE NIFTY 50 data analysis
- 📊 Market microstructure-aware preprocessing
- 📉 Log return computation
- 📈 GARCH(1,1) volatility forecasting
- 📊 Heavy-tailed Student-t distribution fitting
- 📉 Extreme Value Theory (EVT)
- 📈 Generalized Pareto Distribution (GPD)
- 💹 Dynamic Value-at-Risk (VaR)
- 📉 Conditional Value-at-Risk (CVaR)
- 📊 Rolling volatility estimation
- 📈 Distribution comparison
- 📉 Q-Q Plot analysis
- 📊 Goodness-of-fit testing
- 📈 AIC/BIC model comparison
- 📉 Rolling backtesting
- 📊 Financial risk visualization

---

## 📊 Methodology

1. Download hourly NSE NIFTY 50 market data
2. Perform microstructure-aware preprocessing
3. Compute logarithmic returns
4. Forecast volatility using GARCH(1,1)
5. Fit Student-t distribution
6. Model extreme losses using EVT-GPD
7. Estimate Dynamic VaR
8. Estimate Dynamic CVaR
9. Validate statistical models
10. Generate risk analytics and visualizations

---

## 📈 Risk Models Used

- GARCH (1,1)
- Student's t Distribution
- Extreme Value Theory (EVT)
- Generalized Pareto Distribution (GPD)
- Dynamic Value-at-Risk (VaR)
- Conditional Value-at-Risk (CVaR)

---

## 📊 Statistical Validation

The framework evaluates model performance using

- Kolmogorov-Smirnov Test
- Anderson-Darling Test
- Akaike Information Criterion (AIC)
- Bayesian Information Criterion (BIC)
- Rolling Backtesting
- Out-of-Sample Forecasting

---

## 📉 Visualizations

The project generates

- Intraday Return Plots
- Rolling Volatility
- GARCH Volatility Forecast
- Distribution Comparison
- Q-Q Plot
- EVT Tail Modeling
- Dynamic VaR Forecast
- Conditional Volatility Plot

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- yfinance
- arch
- statsmodels

---

## 📂 Repository Structure

```
Stock-Risk-Estimation/
│
├── README.md
├── requirements.txt
├── stock_risk_estimation.ipynb
│
├── outputs/
│   ├── return_plot.png
│   ├── rolling_volatility.png
│   ├── garch_volatility.png
│   ├── distribution_comparison.png
│   ├── qq_plot.png
│   ├── evt_tail_fit.png
│   ├── dynamic_var.png
│   └── conditional_volatility.png
```

---

## 📈 Results

The proposed framework

- Captures heavy-tailed financial returns
- Models volatility clustering using GARCH
- Estimates extreme downside risk using EVT-GPD
- Produces more realistic VaR and CVaR estimates than Gaussian models
- Dynamically adapts to changing market volatility
- Improves financial risk estimation through microstructure-aware preprocessing

---

## 🚀 Future Improvements

- Real-time market monitoring
- Multi-stock portfolio risk estimation
- Cryptocurrency risk analysis
- Deep Learning hybrid models
- LSTM-GARCH integration
- Interactive dashboard using Streamlit
- Live Yahoo Finance integration

---

## 👩‍💻 Author

**Keerthi G**

B.Tech Computer Science and Engineering

Amrita Vishwa Vidyapeetham

---

