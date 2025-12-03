 Multi-Stock Monte Carlo Options Pricing Engine

This project:
- pulls real-time stock & options data from Yahoo Finance
- runs Monte Carlo simulations per-ticker using GBM
- prices calls & puts for multiple strikes
- computes intraday correlation heatmap
- visualizes simulation paths, terminal distributions, and mispricing vs strike
- exports pricing results to CSV

 Features
✔ Real-time market data  
✔ Multi-asset Monte Carlo  
✔ Correlation heatmap from intraday returns  
✔ Real-time option chain integration  
✔ Price path & terminal distribution visualizations  
✔ Systematic pricing of all options  
✔ Excel-ready CSV output  

   Tech Stack
- Python
- NumPy, Pandas
- yfinance
- matplotlib, seaborn

 Example Output

- `correlation_heatmap_intraday.png`
- `mc_options_pricing_multi_ticker_realtime.csv`

---

 Why I did this

I wanted to build a real-time options pricing engine using Monte Carlo simulation and use it to analyze pricing inefficiencies across a selection of liquid tickers.

---

 Next features (roadmap)

- implied volatility extraction
- Greeks computation (delta, gamma, vega, theta)
- multi-asset correlated Monte Carlo
- API integration & GUI dashboard
