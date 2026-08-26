# 📈 Investment Portfolio Analysis & Risk Dashboard

An interactive **Investment Portfolio Analytics Dashboard** built using **Python (Pandas), SQL, and Power BI** to analyze portfolio performance, measure investment risk, optimize asset allocation, and support data-driven investment decisions. The project transforms raw stock market data into actionable insights that help wealth managers monitor portfolio health, evaluate risk, and maximize long-term returns.

---

# 🎯 Project Objective

Develop an end-to-end investment portfolio analytics solution to:

- Analyze portfolio performance across multiple stocks.
- Calculate daily and cumulative investment returns.
- Measure portfolio risk using financial metrics.
- Optimize portfolio allocation using the Efficient Frontier.
- Monitor key investment KPIs through an interactive dashboard.
- Support smarter, data-driven investment decisions.

---

# 💼 Business Value

Wealth management firms monitor multiple investments daily to ensure clients achieve their financial goals while managing risk. Poor-quality financial data and the absence of risk analysis can lead to inaccurate portfolio evaluations and suboptimal investment decisions. This project enables investment analysts to clean and analyze stock market data, evaluate portfolio performance, identify potential risks, optimize asset allocation, and deliver actionable insights through an interactive dashboard.

---

# ❓ Business Questions

- Which 5 stocks gave the highest unrealised profit in our Indian portfolio?
- Calculate month-wise portfolio return for each of the 3 portfolios
- Calculate the Sharpe Ratio for each stock and identify which are not worth holding
- What is the portfolio's Value at Risk (VaR) in ₹ crores at 95% confidence?
- Standardise all date formats and find which months have the most trades
- Convert market_cap_cr from mixed format (₹ string + number) to clean numeric crores
- Detect and fix all OHLC data errors in the dataset
- Compare total portfolio value and return across all 3 portfolios
- Find stocks where analyst says "Sell" but we still hold a large position — conflict alert
- Which NSE stocks outperformed BSE stocks in return % on average?

---

# 📌 Key Performance Indicators (KPIs)


---

# 🛠️ Technology Stack

| Tool | Purpose |
|------|----------|
| **Python (Pandas)** | Data cleaning, preprocessing, and financial analysis |
| **SQL** | Business analysis and KPI calculations |
| **Power BI** | Interactive dashboard and visualization |
| **Jupyter Notebook** | Data exploration and analysis |

---

# 🔄 Project Methodology

## 1️⃣ Data Preparation

- Loaded the stock market dataset using Pandas.
- Removed duplicate records.
- Standardized ticker symbols and sector names.
- Corrected inconsistent date formats.
- Fixed invalid stock prices and market capitalization values.
- Handled missing values.
- Removed unnecessary columns.
- Validated data quality before analysis.

## 2️⃣ Data Analysis

- Calculated daily and cumulative returns.
- Computed CAGR and unrealized Profit & Loss (P&L).
- Measured Volatility, Sharpe Ratio, Beta, VaR, and Maximum Drawdown.
- Performed portfolio optimization using the Efficient Frontier.
- Analyzed stock correlation and portfolio diversification.
- Evaluated overall portfolio performance.

## 3️⃣ Dashboard Development

- Built an interactive Power BI dashboard.
- Designed KPI cards and investment visualizations.
- Added dynamic filters and drill-down functionality.
- Presented actionable insights for portfolio management.

> **Better investment decisions begin with clean, accurate, and well-structured financial data.**

---

# 📊 Dashboard Preview

![Investment Portfolio Dashboard]()

---

# ⚙️ Dashboard Features

- 

---

# 📈 Key Business Insights

- The analysis shows that TECHM, HCLTECH, BHARTIARTL, ULTRACEMCO, and KOTAKBANK are the top five unrealised-profit contributors, generating a combined ₹5,567.22 crore in unrealised gains. TECHM leads with ₹1,603.58 crore, followed by HCLTECH at ₹1,428.93 crore and BHARTIARTL at ₹1,186.89 crore. The top three stocks contribute approximately 76% of the combined gains from these five holdings, indicating that a significant portion of portfolio performance is concentrated in a few stocks. While this highlights strong performance from key holdings, it also suggests that position sizing and diversification should be monitored to manage concentration risk and protect accumulated gains.
- The month-wise analysis shows that MIDCAP_PORTFOLIO delivered the strongest upside during several periods, including 14.40% in Jan-2020, 14.09% in Aug-2020, and 13.36% in Jun-2022, but also experienced higher downside volatility, falling 19.57% in Oct-2024. NIFTY50_PORTFOLIO appears relatively more stable, with its strongest month being 10.39% in Jul-2024, while SECTORAL_PORTFOLIO produced several strong positive months, including 12.05% in Apr-2020 and 12.80% in Dec-2022. However, the unusually large returns of 7,041.01%, 11,060.38%, 10,347.04%, 8,895.74%, and 5,049.75% are clear data-quality outliers and should be investigated before using the results for investment decisions. Overall, MIDCAP offers higher return potential but greater volatility, NIFTY50 provides comparatively consistent performance, and SECTORAL shows mixed but occasionally strong returns.
- KOTAKBANK delivered the best risk-adjusted performance with a Sharpe Ratio of 1.19, followed by ULTRACEMCO (1.17) and BHARTIARTL (1.13). Overall, all 25 stocks generated positive Sharpe Ratios, indicating that they provided returns above the risk-free rate relative to their volatility. However, NESTLEIND (0.35), WIPRO (0.36), HINDUNILVR (0.39), and ONGC (0.39) had the weakest risk-adjusted performance and should be reviewed for portfolio optimisation.
- The portfolio’s 95% Value at Risk (VaR) is ₹4.17 lakh, indicating that the portfolio is expected to limit its daily loss to approximately ₹4.17 lakh on 95% of trading days. However, there is a 5% probability of experiencing a daily loss exceeding this level, highlighting the portfolio’s exposure to potential short-term market risk.
- The analysis shows that February 2024 recorded the highest trading activity with 133 trades, followed by January 2023 (126) and September 2024 (126). Trading activity was generally stronger during 2023–2024, while several months in 2020–2022 recorded comparatively lower activity. Overall, the results indicate uneven trading volume across months, with February 2024 representing the peak period for transaction activity.
- The market_cap_cr field contained mixed formats, including rupee-formatted strings and numeric values. The data was standardised by removing currency symbols, commas, and the Cr suffix, then converting all values into a consistent numeric value in ₹ crores. This ensures accurate market-cap comparisons and prevents data-type errors during portfolio analysis, aggregation, and financial calculations.
- The MIDCAP_PORTFOLIO was the strongest performer, generating a 514.76% return and reaching a total portfolio value of approximately ₹361.97 crore. The SECTORAL_PORTFOLIO ranked second with a 397.89% return and a value of ₹259.62 crore, while the NIFTY50_PORTFOLIO generated the lowest return of 76.33%, with a value of ₹106.88 crore. Overall, the results indicate that the Midcap strategy significantly outperformed both the Sectoral and Nifty 50 portfolios, making it the best-performing strategy in this analysis.
- NESTLEIND represents a significant portfolio conflict, as the stock is rated SELL by analysts while multiple large positions are still being held. The largest position is 1,711 shares worth approximately ₹4.48 crore, with several additional positions exceeding ₹3 crore.
- NSE stocks strongly outperformed BSE stocks, delivering an average return of 1,015.45% versus 54.11% for BSE, indicating significantly stronger performance from NSE-listed stocks in this portfolio.

---

# 💡 Business Recommendations

- 

---

# 📈 Business Impact

The Investment Portfolio Analysis Dashboard helps wealth managers:

- 

---

# 🧠 Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Python (Pandas)
- SQL
- Power BI
- Financial Data Analysis
- Portfolio Performance Analysis
- Risk Analytics
- Portfolio Optimization
- KPI Reporting
- Dashboard Design
- Business Intelligence
- Data Visualization

---

# 🚀 Project Outcome

Successfully transformed raw stock market data into an interactive **Investment Portfolio Analysis & Risk Dashboard** that evaluates portfolio performance, measures investment risk, optimizes asset allocation, and delivers actionable insights for wealth managers. The solution enables informed investment decisions, improved portfolio diversification, and effective long-term portfolio management.

---

# 👨‍💻 Author

**Shiv Suthar**

---

⭐ **If you found this project useful, consider giving it a Star ⭐ on GitHub!**
