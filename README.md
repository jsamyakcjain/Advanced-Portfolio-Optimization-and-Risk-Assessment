# Advanced-Portfolio-Optimization-and-Risk-Assessment

This repository contains a Jupyter Notebook (Quant Project.ipynb) that demonstrates a quantitative approach to portfolio construction and risk management. The project involves downloading historical stock data, calculating returns, performing portfolio optimization using various techniques, and assessing portfolio risk using metrics like Value at Risk (VaR) and Conditional Value at Risk (CVaR) through Monte Carlo simulations.

Features
Data Acquisition: Downloads historical adjusted close prices for a diversified universe of stocks and ETFs using yfinance.

Portfolio Definition: Defines a structured universe of assets across different sectors (Utilities, Healthcare, Technology, Financials) and market capitalization groups (Large, Mid, Small Cap, and Equity ETFs).

Returns Calculation: Computes daily log returns for all selected assets.

Descriptive Statistics: Provides summary statistics for the asset price data.

Capital Asset Pricing Model (CAPM) Analysis: Estimates asset betas against a market proxy (e.g., SPY) to understand systematic risk.

Portfolio Optimization:

Minimum Volatility Portfolio: Constructs a portfolio designed to minimize overall risk for a given set of assets.

Maximum Sharpe Ratio Portfolio: Identifies the portfolio that maximizes risk-adjusted returns (Sharpe Ratio).

Efficient Frontier: Plots the efficient frontier, illustrating the trade-off between portfolio risk and return.

Monte Carlo Simulation: Performs Monte Carlo simulations to forecast portfolio returns and estimate potential losses.

Value at Risk (VaR) and Conditional Value at Risk (CVaR): Calculates Monte Carlo VaR and CVaR to quantify downside risk at specified confidence levels.

Time Series Analysis: Visualizes cumulative returns for selected large, mid, and small-cap stocks.

Detailed Correlation Analysis: Provides correlation heatmaps for average returns across market cap groups and for individual stocks within each market cap group.

Technologies Used
Python 3.x

Pandas for data manipulation and analysis

NumPy for numerical operations

Matplotlib and Seaborn for data visualization

yfinance for downloading financial data

CVXPY for convex optimization

SciPy for scientific computing, including optimization algorithms

Scikit-learn for linear regression analysis (e.g., CAPM beta calculation)

Installation
To set up the project locally, follow these steps:

Clone the repository:

git clone https://github.com/YourUsername/Advanced-Portfolio-Optimization-and-Risk-Assessment.git
cd Advanced-Portfolio-Optimization-and-Risk-Assessment

Create a virtual environment (recommended):

python -m venv env
source env/bin/activate  # On Windows: .\env\Scripts\activate

Install the required packages:

pip install -r requirements.txt

Install Jupyter Notebook:

pip install notebook

Usage
To run the analysis:

Launch Jupyter Notebook:

jupyter notebook

Open Quant Project.ipynb:
Select the Quant Project.ipynb file from the Jupyter Notebook interface to open it.

Run the cells: Execute the cells sequentially to reproduce the analysis and generate the plots.

