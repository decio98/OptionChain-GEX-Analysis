# 📊 Option Chain GEX Analysis

This project aims to develop a Python framework for extracting option chain data from financial markets (specifically SPY ETF) and calculating Gamma Exposure (GEX) and Implied Volatility GEX (IV GEX) in order to analyze market maker positioning and identify potential "sticky" price levels.

## Project Objective
- Automatically extract option chain data via API (AlphaVantage or other data providers).
- Calculate Gamma Exposure (GEX) to assess market makers' hedging flows.
- Calculate IV GEX to identify high-interest price levels ("sticky strikes").
- Provide visual representation of Greeks and critical levels through charts.

## Technologies & Tools
- Python 3.x
- pandas / numpy / scipy
- requests (API calls)
- matplotlib (data visualization)


## Setup Instructions
1. Create a virtual environment and install required packages:
```bash
pip install -r requirements.txt
