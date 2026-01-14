## Project Overview
This project implements a mean-reversion trading strategy using Python. It identifies overbought and oversold conditions in S&P 500 stocks to execute automated buy/sell orders.

## Key Features
- **Library Stack:** `Backtesting.py`, `pandas-ta`, `yfinance`.
- **Strategy Logic:** Buys when RSI < 30 (Oversold), Sells when RSI > 70 (Overbought).
- **Risk Management:** Position sizing set to 95% of equity to prevent margin calls.
- **Performance:** Achieved a Sharpe Ratio of on Google (GOOG) stock over a 3-year period.

## How to Run
1. Clone the repo.
2. Install dependencies: `pip install backtesting yfinance pandas_ta`.
3. Run the notebook: `jupyter notebook`.
