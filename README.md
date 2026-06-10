# Stock Analysis Suite

A Python-based financial analysis toolkit for evaluating individual stocks and optimizing multi-asset portfolios. Built using real-time Yahoo Finance market data, the suite covers everything from candlestick charting and Bollinger Bands to Monte Carlo simulation and efficient frontier visualization.

---

## Modules

### 1. Single Stock Analysis (`single_stock_analysis.py`)
Interactive technical analysis for any publicly traded stock.
- Downloads historical OHLCV data via Yahoo Finance (yfinance)
- Calculates daily returns and classifies market movement trends
- Generates candlestick charts with 20-day and 50-day moving averages
- Plots Bollinger Bands for volatility and breakout analysis
- Exports all charts as interactive HTML files and high-resolution PNGs

### 2. Multi-Asset Portfolio Analysis (`portfolio_analysis.py`)
End-to-end portfolio construction, backtesting, and optimization engine.
- Supports any number of user-defined assets confirmed via live ticker search
- Calculates annualized return, volatility, Sharpe ratio, and ROI
- Runs Monte Carlo simulations across thousands of random weight allocations
- Identifies the maximum Sharpe ratio (optimal) portfolio
- Visualizes the efficient frontier with an interactive scatter plot
- Compares random-weight vs. equal-weight portfolio performance

---

## Installation
```bash
pip install -r requirements.txt
```

## Usage
```bash
python single_stock_analysis.py
python portfolio_analysis.py
```
Both scripts are fully interactive — they prompt the user for company names, date ranges, and investment amounts at runtime.

---

## Skills Demonstrated
| Area | Tools & Techniques |
|---|---|
| Data Collection | yfinance, Yahoo Finance API, Live Ticker Search |
| Financial Analysis | Daily Returns, Volatility, Sharpe Ratio, ROI, MPT |
| Technical Indicators | Bollinger Bands, SMA (20/50-day), Candlestick Charts |
| Portfolio Optimization | Monte Carlo Simulation, Efficient Frontier, Covariance Matrix |
| Visualization | Plotly (Interactive), Matplotlib, Seaborn Pairplot |
| Software Design | Modular Functions, Input Validation, Error Handling, File Export |
