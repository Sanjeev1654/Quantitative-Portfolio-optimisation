
# Quantitative Portfolio Optimization

This project implements **Modern Portfolio Theory (MPT)** to construct and backtest an optimal portfolio of stocks using Python.  
It applies **random portfolio simulation**, **Sharpe ratio maximization**, and **risk-adjusted performance metrics** to find the best allocation of assets.

---

## 📊 Mathematical Concepts Used
- **Log Returns**: Calculated using `ln(P_t / P_{t-1})` for stability and aggregation.
- **Annualized Return (CAGR)**: 
  \\[
  CAGR = (1 + R_{total})^{\\frac{252}{N}} - 1
  \\]
- **Annualized Volatility**: 
  \\[
  \\sigma_{annual} = \\sigma_{daily} \\times \\sqrt{252}
  \\]
- **Sharpe Ratio**:  
  \\[
  S = \\frac{CAGR - R_f}{\\sigma}
  \\]
- **Sortino Ratio**:  
  Penalizes only downside risk.  
- **Maximum Drawdown**: Largest observed peak-to-trough decline.  
- **Value at Risk (VaR) & Conditional VaR (CVaR)**: Historical simulation method for tail risk.

---

## 🛠️ Requirements
This project is written in **Python 3** and uses the following libraries:

- **NumPy** – Numerical computations
- **Pandas** – Data handling
- **Matplotlib** – Plotting
- **SciPy** – Optimization (`SLSQP` for Sharpe maximization)
- **yFinance** – Downloading stock price data

---

