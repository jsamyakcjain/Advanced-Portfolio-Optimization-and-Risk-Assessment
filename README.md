# Advanced-Portfolio-Optimization-and-Risk-Assessment

This repository contains a Jupyter Notebook (Advanced-Portfolio-Optimization-and-Risk-Assessment.ipynb) that demonstrates a quantitative approach to portfolio construction and risk management. The project involves downloading historical stock data, calculating returns, performing portfolio optimization using various techniques, and assessing portfolio risk using metrics like Value at Risk (VaR) and Conditional Value at Risk (CVaR) through Monte Carlo simulations.

# Features

1) Data Acquisition: Downloads historical adjusted close prices for a diversified universe of stocks and ETFs using yfinance.

2) Portfolio Definition: Defines a structured universe of assets across different sectors (Utilities, Healthcare, Technology, Financials) and market capitalization groups (Large, Mid, Small Cap, and Equity ETFs).

3) Returns Calculation: Computes daily log returns for all selected assets.

4) Descriptive Statistics: Provides summary statistics for the asset price data.

5) Capital Asset Pricing Model (CAPM) Analysis: Estimates asset betas against a market proxy (e.g., SPY) to understand systematic risk.

6) Portfolio Optimization:

  6.1) Minimum Volatility Portfolio: Constructs a portfolio designed to minimize overall risk for a given set of assets.

  6.2) Maximum Sharpe Ratio Portfolio: Identifies the portfolio that maximizes risk-adjusted returns (Sharpe Ratio).

  6.3) Efficient Frontier: Plots the efficient frontier, illustrating the trade-off between portfolio risk and return.

7) Monte Carlo Simulation: Performs Monte Carlo simulations to forecast portfolio returns and estimate potential losses.

8) Value at Risk (VaR) and Conditional Value at Risk (CVaR): Calculates Monte Carlo VaR and CVaR to quantify downside risk at specified confidence levels.

9) Time Series Analysis: Visualizes cumulative returns for selected large, mid, and small-cap stocks.

10) Detailed Correlation Analysis: Provides correlation heatmaps for average returns across market cap groups and for individual stocks within each market cap group.

# Libraries Used

Pandas for data manipulation and analysis

NumPy for numerical operations

Matplotlib and Seaborn for data visualization

yfinance for downloading financial data

CVXPY for convex optimization

SciPy for scientific computing, including optimization algorithms

Scikit-learn for linear regression analysis (e.g., CAPM beta calculation)


To run the analysis:

Launch Jupyter Notebook:

Open the Notebook: Select the Advanced-Portfolio-Optimization-and-Risk-Assessment.ipynb file to open it in your browser.

Run the cells: Execute the cells sequentially to reproduce the analysis and generate the plots.

