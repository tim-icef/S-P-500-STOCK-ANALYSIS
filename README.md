# S-P-500-STOCK-ANALYSIS
S&amp;P 500 stock analysis pipeline built with Python, PostgreSQL and psycopg2. Calculates daily/log returns, rolling statistics, volatility regimes and risk metrics (Sharpe, max drawdown, Calmar) across ~500 stocks from 2013-2018 (kaggle dataset).

Reqs:
pandas
psycopg2-binary

Dataset: [S&P 500 Stocks — Kaggle](https://www.kaggle.com/datasets/andrewmvd/sp-500-stocks) put it in the project files folder
!! Create a file containing your PostgreSQL password and edit the pwd path
