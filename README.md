# 📈 Investment Portfolio Analysis & Risk Dashboard

An interactive **Web-Based Investment Portfolio Analytics Dashboard** built using **Python (Pandas), SQL, HTML, CSS, and JavaScript** to analyze portfolio performance, evaluate investment risk, monitor portfolio allocation, and support data-driven investment decisions.

The project transforms raw stock market data into actionable insights that help wealth managers and investment analysts monitor portfolio health, evaluate holdings, understand sector exposure, compare portfolio performance, and identify potential investment risks.

---

# 🎯 Project Objective

Develop an end-to-end investment portfolio analytics solution to:

- Analyze portfolio performance across multiple stocks and portfolios.
- Monitor portfolio value and unrealised Profit & Loss (P&L).
- Evaluate stock valuation using P/E ratios and dividend yield.
- Analyze sector allocation and portfolio concentration.
- Compare portfolio performance across different portfolio types.
- Monitor analyst recommendations across current holdings.
- Measure investment risk using financial risk metrics.
- Support smarter, data-driven investment decisions through an interactive web dashboard.

---

# 💼 Business Value

Wealth management teams need clear visibility into portfolio performance, valuation, risk, and diversification to make informed investment decisions.

This project provides a centralized analytics solution to:

- 📊 Monitor overall portfolio performance.
- 💰 Track portfolio value and unrealised P&L.
- 🏦 Identify sector concentration and diversification risks.
- 📈 Evaluate stock valuation and dividend yield.
- 🎯 Compare portfolio performance across investment strategies.
- 🚨 Monitor BUY, HOLD, and SELL analyst recommendations.
- 🔍 Identify major portfolio holdings by market value.
- 📌 Support data-driven portfolio management decisions.

---


# ❓ Business Questions

- Which 5 stocks generated the highest unrealised profit?
- What are the month-wise returns for each portfolio?
- Which stocks have the best and worst Sharpe Ratios?
- Which stocks may not be worth holding based on risk-adjusted performance?
- What is the portfolio's Value at Risk (VaR) at 95% confidence?
- Which months recorded the highest trading activity?
- How can mixed market capitalization formats be standardized?
- Are there any OHLC data quality issues?
- Which portfolio has the highest overall return and value?
- Are there stocks rated **SELL** by analysts while still holding large positions?
- Which exchange, NSE or BSE, generated higher average returns?
- Is the portfolio over-concentrated in any sector?
- Which sector has the highest average P/E ratio?
- Which sector generates the highest dividend income?
- How do portfolio types compare in terms of average return?

---

# 📌 Key Performance Indicators (KPIs)

| KPI | Dashboard Value / Description |
|------|-------------------------------|
| 💰 **Total Portfolio Value** | ₹3.78B |
| 📉 **Total Unrealised P&L** | ₹-3.46Cr |
| 📊 **Average P/E Ratio** | 44.0 |
| 💵 **Average Dividend Yield** | 2.03% |

> **Dashboard snapshot:** 5,017 position records across 25 NSE/BSE stocks for the 2020–2024 period.

---

# 🛠️ Technology Stack

| Tool / Technology | Purpose |
|------|----------|
| **Python (Pandas)** | Data cleaning, preprocessing, and financial analysis |
| **SQL** | Business analysis, KPI calculations, and portfolio insights |
| **HTML** | Dashboard structure and layout |
| **CSS** | Dashboard styling, responsive layout, and visual design |
| **JavaScript** | Interactive filtering, calculations, charts, and client-side functionality |
| **Web-Based Dashboard** | Single-page interactive analytics and visualization |
| **Jupyter Notebook** | Data exploration and financial analysis |

---

# 🔄 Project Methodology

## 1️⃣ Data Preparation

- Loaded the stock market dataset using Pandas.
- Removed duplicate records.
- Standardized ticker symbols and sector names.
- Corrected inconsistent date formats.
- Fixed invalid stock prices.
- Detected and corrected OHLC data errors.
- Standardized market capitalization values.
- Converted mixed market-cap formats into numeric ₹ crores.
- Handled missing values.
- Removed unnecessary columns.
- Validated data quality before analysis.

## 2️⃣ Financial Analysis

- Calculated daily and cumulative returns.
- Calculated month-wise portfolio returns.
- Computed unrealised Profit & Loss (P&L).
- Calculated Volatility, Sharpe Ratio, Beta, VaR, and Maximum Drawdown.
- Compared portfolio performance across three portfolios.
- Analyzed stock and sector performance.
- Evaluated stock correlation and diversification.
- Analyzed analyst recommendations.
- Evaluated sector valuation using P/E ratios.
- Analyzed dividend income and dividend yield.

## 3️⃣ Portfolio Optimization

- Applied **Efficient Frontier** methodology.
- Evaluated the relationship between portfolio return and risk.
- Analyzed diversification opportunities.
- Evaluated risk-adjusted portfolio performance.
- Identified potential opportunities for improving asset allocation.

## 4️⃣ Dashboard Development

- Built a **Single-Page, Client-Side Web Dashboard**.
- Designed interactive KPI cards.
- Created portfolio performance and P&L visualizations.
- Added portfolio, analyst rating, and sector filters.
- Added interactive stock and portfolio analysis.
- Presented dynamic financial insights.
- Designed a clean and user-friendly interface for investment monitoring.

> **Better investment decisions begin with clean, accurate, and well-structured financial data.**

---

# 📊 Dashboard Preview

![Investment Portfolio Analysis & Risk Dashboard](https://github.com/sutharshiv482-coder/Investment-Portfolio-Analysis-Risk-Dashboard/blob/main/Investment%20Portfolio%20Analysis%20%26%20Risk%20Dashboard%20-%20Google%20Chrome%2030-08-2026%2021_31_10.png)

---

# ⚙️ Dashboard Features

- 💰 **Portfolio Value KPI** – Monitor total portfolio market value.
- 📉 **Unrealised P&L KPI** – Track unrealised portfolio gains and losses.
- 📊 **Average P/E Ratio KPI** – Monitor portfolio valuation.
- 💵 **Average Dividend Yield KPI** – Track average dividend yield across holdings.
- 📈 **Portfolio Value & P&L Trend** – Analyze yearly portfolio value and P&L movement from 2020–2024.
- 🏦 **Sector Allocation** – Visualize portfolio exposure across sectors.
- 🏆 **Top Holdings by Value** – Identify the largest holdings based on current market value.
- 🎯 **Analyst Rating Split** – Compare BUY, HOLD, and SELL recommendations.
- 📊 **Valuation Map** – Analyze P/E ratio against dividend yield.
- 📈 **Average Return by Portfolio Type** – Compare MIDCAP, NIFTY50, and SECTORAL portfolio performance.
- 🎛️ **Portfolio Filters** – Filter analysis by MIDCAP, NIFTY50, and SECTORAL portfolios.
- 🏷️ **Analyst Rating Filters** – Analyze holdings based on BUY, HOLD, or SELL recommendations.
- 🏦 **Sector Filters** – Filter the dashboard by individual sectors.
- 🖱️ **Interactive Cross-Filtering** – Select charts and holdings to filter the overall dashboard.
- 💡 **Dynamic Portfolio Analytics** – Dashboard visuals update based on selected filters.
- 🖥️ **Single-Page Client-Side Interface** – All dashboard analysis is presented through a unified web-based interface.

---

# 📈 Key Business Insights

### 🏆 Top Unrealised Profit Contributors

- **TECHM, HCLTECH, BHARTIARTL, ULTRACEMCO, and KOTAKBANK** were the top five unrealised-profit contributors, generating a combined **₹5,567.22 crore** in unrealised gains.
- **TECHM** led with **₹1,603.58 crore**, followed by **HCLTECH (₹1,428.93 crore)** and **BHARTIARTL (₹1,186.89 crore)**.
- The top three stocks contributed approximately **76%** of the combined gains from these five holdings, highlighting potential concentration risk.

### 📅 Portfolio Return Analysis

- **MIDCAP_PORTFOLIO** delivered strong upside during several periods, including **14.40% in Jan-2020**, **14.09% in Aug-2020**, and **13.36% in Jun-2022**.
- However, the portfolio also experienced significant downside, falling **19.57% in Oct-2024**.
- **NIFTY50_PORTFOLIO** showed comparatively stable performance, while **SECTORAL_PORTFOLIO** produced several strong positive months.
- Extremely high monthly returns such as **7,041.01%, 11,060.38%, 10,347.04%, 8,895.74%, and 5,049.75%** were identified as data-quality outliers and should be investigated before using the results for investment decisions.

### ⚖️ Risk-Adjusted Performance

- **KOTAKBANK** delivered the best Sharpe Ratio at **1.19**, followed by **ULTRACEMCO (1.17)** and **BHARTIARTL (1.13)**.
- All 25 stocks generated positive Sharpe Ratios.
- **NESTLEIND (0.35), WIPRO (0.36), HINDUNILVR (0.39), and ONGC (0.39)** recorded the weakest Sharpe Ratios and should be reviewed for portfolio optimization.

### ⚠️ Portfolio Value at Risk

- The portfolio's **95% VaR is approximately ₹4.17 lakh**, indicating the estimated daily loss threshold at the 95% confidence level.
- There remains a **5% probability** of experiencing a daily loss greater than the estimated VaR, highlighting the importance of short-term risk monitoring.

### 📅 Trading Activity

- **February 2024** recorded the highest trading activity with **133 trades**.
- **January 2023** and **September 2024** followed with **126 trades each**.
- Trading activity was generally stronger during **2023–2024**.

### 💹 Market Capitalization Data Quality

- The `market_cap_cr` field contained mixed formats, including rupee-formatted strings and numeric values.
- Currency symbols, commas, and the **Cr** suffix were removed before converting values into standardized numeric ₹ crores.
- This improved consistency and enabled accurate market-cap aggregation and comparison.

### 🏆 Portfolio Comparison

| Portfolio | Portfolio Value | Return |
|------|------:|------:|
| **MIDCAP_PORTFOLIO** | ₹361.97 crore | **514.76%** |
| **SECTORAL_PORTFOLIO** | ₹259.62 crore | **397.89%** |
| **NIFTY50_PORTFOLIO** | ₹106.88 crore | **76.33%** |

- **MIDCAP_PORTFOLIO** was the strongest-performing strategy with a **514.76% return**.
- **SECTORAL_PORTFOLIO** ranked second with **397.89%**.
- **NIFTY50_PORTFOLIO** generated the lowest return at **76.33%**.

### 🚨 Analyst Rating Conflict

- **NESTLEIND** represents a significant portfolio conflict because analysts rated the stock **SELL** while multiple large positions were still being held.
- The largest position consisted of **1,711 shares**, worth approximately **₹4.48 crore**.
- This highlights the need to regularly review portfolio holdings against current analyst recommendations.

### 📊 Exchange Performance

- **NSE stocks** significantly outperformed **BSE stocks**, generating an average return of **1,015.45%** compared with **54.11%** for BSE stocks.

### 🏦 Sector Concentration Risk

- The portfolio was over-concentrated in **Technology**, with **44.06% allocation**.
- This exceeds the defined **35% risk threshold by 9.06 percentage points**.
- High sector concentration increases exposure to sector-specific market volatility and highlights the need for greater diversification.

### 📊 Sector Valuation

- The **Automobile** sector recorded the highest average P/E ratio at **42.92**.
- This indicates a premium valuation and strong investor growth expectations, while also increasing the risk of overvaluation if future earnings fail to meet expectations.

### 💵 Dividend Income

- **Technology** generated the highest dividend income at approximately **₹48.53 crore**.
- Dividend sustainability should additionally be evaluated using payout ratio, earnings, and cash-flow metrics.

---

# 💡 Business Recommendations

- 🏦 **Reduce sector concentration:** Review the Technology allocation of **44.06%** and consider greater diversification.
- 📊 **Monitor top holdings:** Closely monitor major unrealised-profit contributors to protect accumulated gains.
- ⚖️ **Focus on risk-adjusted performance:** Review stocks with consistently weaker Sharpe Ratios.
- ⚠️ **Strengthen risk monitoring:** Use VaR, volatility, Beta, and Maximum Drawdown together to monitor portfolio risk.
- 🚨 **Review analyst conflicts:** Investigate large holdings with SELL recommendations.
- 📈 **Validate extreme returns:** Investigate unusually high monthly returns before using them for strategic decisions.
- 🏦 **Improve diversification:** Reduce dependence on individual sectors and stocks.
- 💵 **Evaluate dividend sustainability:** Consider payout ratios, earnings, and cash flows alongside dividend yield.
- 🎯 **Use portfolio optimization:** Apply Efficient Frontier analysis to identify a better balance between expected return and risk.
- 🔄 **Monitor portfolio performance regularly:** Track portfolio value, P&L, sector allocation, valuation, and analyst ratings.

---

# 📈 Business Impact

The Investment Portfolio Analysis & Risk Dashboard helps wealth managers and investment analysts:

- 📈 Identify major profit and return drivers.
- 💰 Monitor portfolio value and unrealised P&L.
- ⚠️ Detect portfolio risk and concentration exposure.
- ⚖️ Evaluate risk-adjusted investment performance.
- 🎯 Improve asset allocation decisions.
- 🏦 Strengthen portfolio diversification.
- 🚨 Identify analyst recommendation conflicts.
- 📊 Compare portfolio strategies effectively.
- 🔍 Improve financial data quality.
- 🚀 Support faster, data-driven investment decisions.

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
