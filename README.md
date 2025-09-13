# Stock-Market-Analysis
# Objective:
This project analyzes stock performance using key metrics such as daily return percentage, volatility, trade value, max high and min low prices, average volume, and buy/sell volumes. It provides insights into trading patterns, risk, and investment opportunities.

# Key Features of dataset: 
- dim_exchange → Exchange details (ID, name, country, currency)
- dim_sector → Industry/sector classification
- dim_company → Company details (linked to sector & exchange)
- dim_trader → Trader information
- dim_portfolio → Portfolio details
- dim_calendar → Dates (helps in time-based analysis)
- fact_daily_prices → Stock daily prices (open, close, high, low, volume, etc.)
- fact_dividends → Dividend payouts
- fact_splits → Stock split events
- fact_orders → Orders placed in the market
- fact_trades → Executed trades
- fact_positions_snapshot → Portfolio holdings at a snapshot in time
