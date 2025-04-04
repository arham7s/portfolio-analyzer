# 📊 Multi-Dimensional Portfolio Risk and Performance Analyzer

🚀 Live App: [Click here to launch](https://portfolioanalyzerpy.streamlit.app/)

This is an advanced Streamlit-based web application that empowers investors, analysts, and enthusiasts to analyze, optimize, and manage portfolios using a rich set of financial metrics and simulation techniques.

---

## Features

### 🔧 Portfolio Analysis
- Input up to 10 stock tickers with custom weight allocations.
- Select custom date ranges for historical analysis.
- Fetch historical data via FinancialModelingPrep + fallback to Yahoo Finance (`yfinance`).

### 📈 Performance Metrics
- CAGR, Volatility, Sharpe Ratio (stock-level & portfolio-level).
- Correlation heatmaps and price movement visualizations.

### 🧮 Portfolio Optimization
- Efficient Frontier (10,000 simulations).
- Optimization strategies:
  - Max Sharpe Ratio
  - Min Volatility
  - Max Return
- Side-by-side pie charts and performance comparisons.

### 🔐 Risk Analytics
- Value at Risk (VaR): Historical, Variance-Covariance, Monte Carlo
- Conditional VaR (CVaR), Expected Shortfall
- Rolling Volatility, Calmar Ratio, Maximum Drawdown
- Beta calculation with benchmark selection (e.g., S&P 500, NIFTY 50)

### 📊 Advanced Insights
- Rolling Sharpe Ratio & Rolling Beta time series
- Risk Attribution: Contribution of each stock to portfolio volatility
- Monte Carlo simulation of future returns
- Drawdown analysis
- Extreme Value Theory for tail risk (EVT)
- Factor Exposure Analysis using the Fama-French 3-Factor Model

---

## 📋 How to Use

1. **Enter portfolio value**, number of stocks, and their weights.
2. Choose **start & end dates** for analysis.
3. Click **"Fetch Data"** to load performance charts & metrics.
4. Optionally:
   - Run **Portfolio Optimization** to get optimal weights.
   - Run **Risk Analytics** for VaR, drawdown, and simulations.

---

## 📚 Tech Stack

- Python
- [Streamlit](https://streamlit.io/)
- Plotly
- yFinance
- Statsmodels
- NumPy, Pandas, SciPy

---

## 👤 Author

**Project by Arham Shah**

Connect with me on:
- [GitHub](https://github.com/arhamshahwork)
- 📧 arhamshahwork@gmail.com

---

## 🏁 Local Deployment

```bash
git clone https://github.com/yourusername/portfolio-analyzer.git
cd portfolio-analyzer
pip install -r requirements.txt
streamlit run app.py
