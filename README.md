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

# KPI's:
- Average Volume of Stocks for different companies
- Total Trade Value per Ccompany
- Average Daily Return of stocks
- Total Buy & Sell of Stocks for all companies
- Volatality of Stocks of all companies
- 52 Week High & Low Stock price

# Process:
- Data Gathering & Cleaning - Gather Stock Market dataset and clean it by handling missing values, standardizing names, and formatting columns.
- Define Key Metrics (KPIs) - Focus on insights like trade value, average stocks volume, daily return rate, volatality etc.
- Dashboard Design – Use charts/maps/tables (e.g., Trade value, Average Daily return of stocks, KPI cards for Max Opening Price, Total orders etc.).
- Interactivity & Filters – Add slicers for company name to let users drill down and explore restaurant performance easily.

# Recommendations:
- HDFC Bank has the highest trade value, so it seems to be very active and important in the market.
- Reliance has the highest average volume of shares traded, showing strong investor interest.
- Amazon and Infosys show positive daily returns, meaning they are giving small but steady gains.
- Stock volatility is highest for Apple and HDFC Bank, which means their prices fluctuate more, carrying higher risk but also higher potential reward.
- The 52-week high and low chart shows HDFC Bank reaching the highest peak price, while Apple and Microsoft are closer to the lower side.
