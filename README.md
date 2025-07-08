# Smart-Portfolio-Optimizer-Risk-Aware-Multi-Asset-Analysis-Using-Python
A Python-based portfolio optimizer that analyzes multi-asset ETF data, calculates key performance and risk metrics (Sharpe Ratio, drawdown, volatility), and constructs an efficient portfolio using Sharpe-maximizing optimization. Results are visualized and stored in a queryable SQLite database.


##  Features

- Downloaded historical ETF data via `yfinance`
- Calculated key performance metrics:
  - Daily returns
  - Cumulative growth
  - Annualized volatility
  - Sharpe Ratio
  - Max Drawdown
  - Correlation matrix
- Built a portfolio with custom weights and compared it with an optimized version
- Used `scipy.optimize` to maximize Sharpe Ratio
- Stored results in a SQLite database for analysis/reporting
- Visualized:
  - Manual vs Optimized growth
  - Risk-adjusted metric comparison
  - Optimized asset allocation pie chart

##  Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- `yfinance` for market data
- `scipy.optimize` for Sharpe Ratio optimization
- SQLite for data storage

##  Files

- `Smart_Portfolio_Optimizer.ipynb` – Main notebook
- `portfolio.db` – Contains weights, returns, metrics
- `README.md` – Project summary
- `requirements.txt` – Python dependencies

##  How to Run

bash
pip install -r requirements.txt
jupyter notebook
