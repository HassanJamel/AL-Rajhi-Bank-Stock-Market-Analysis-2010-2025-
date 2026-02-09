# AL Rajhi Bank Stock Market Analysis (2010-2025)

## 📊 Project Overview

**AL Rajhi Bank Historical Stock Data Analysis** - A comprehensive dataset containing 15+ years of daily trading data for AL Rajhi Bank (Ticker: 1120.SR), one of the largest Islamic banks in the world and the largest bank in Saudi Arabia by market capitalization.

---

## 🏷️ SEO-Optimized Project Information

### Project Title

**AL Rajhi Bank Stock Price Analysis & Forecasting (2010-2025) | Saudi Stock Market Data | Tadawul 1120.SR**

### Project Description

Comprehensive historical stock market dataset for AL Rajhi Bank (1120.SR), Saudi Arabia's premier Islamic banking institution listed on the Tadawul (Saudi Stock Exchange). This dataset spans from March 2010 to December 2025, providing 3,926 daily trading records including Open, High, Low, Close prices, and Volume data. Ideal for technical analysis, machine learning price prediction models, time-series forecasting, and financial research on the Middle Eastern banking sector.

---

## 🔖 Top 5 Kaggle Tags

1. **`stock-market`** - Financial market analysis and trading data
2. **`time-series`** - Daily sequential data suitable for time-series forecasting
3. **`finance`** - Banking and financial sector analysis
4. **`saudi-arabia`** - Middle Eastern market focus and regional financial data
5. **`islamic-banking`** - Unique focus on Shariah-compliant banking institution

---

## 📋 Dataset Column Details

| Column     | Data Type         | Description                          | Sample Values            |
| ---------- | ----------------- | ------------------------------------ | ------------------------ |
| **Date**   | Date (YYYY-MM-DD) | Trading date                         | 2010-03-03 to 2025-12-31 |
| **Price**  | Float             | Adjusted closing price               | 16.90 - 100.10 SAR       |
| **Close**  | Float             | Closing price for the trading day    | Daily close price        |
| **High**   | Float             | Highest price during trading session | Intraday maximum         |
| **Low**    | Float             | Lowest price during trading session  | Intraday minimum         |
| **Open**   | Float             | Opening price at market start        | Session opening price    |
| **Volume** | Integer           | Number of shares traded              | 0 - 18,467,573 shares    |

### Dataset Metadata

- **Ticker Symbol**: 1120.SR
- **Total Records**: 3,926 daily observations
- **File Format**: CSV (Comma-Separated Values)
- **File Size**: ~364 KB

---

## 🌍 Coverage Information

### Data Coverage

- **Sector**: Banking & Financial Services
- **Sub-sector**: Islamic Banking (Shariah-compliant)
- **Market**: Middle East and North Africa (MENA) region
- **Exchange**: Tadawul (Saudi Stock Exchange)
- **Index Inclusion**: TASI (Tadawul All Share Index), MSCI Emerging Markets

### Company Profile

AL Rajhi Bank is:

- The **largest Islamic bank globally** by market capitalization
- The **2nd largest bank in Saudi Arabia**
- A founding member of Saudi Arabia's banking sector
- Listed on Tadawul since the exchange's inception
- A major component of Saudi Arabia's Vision 2030 financial sector

---

## 📅 Temporal & Geospatial Scope

### Temporal Coverage

| Parameter              | Value                      |
| ---------------------- | -------------------------- |
| **Start Date**         | 03/03/2010                 |
| **End Date**           | 12/31/2025                 |
| **Duration**           | ~15 years, 10 months       |
| **Frequency**          | Daily (Business days only) |
| **Total Trading Days** | 3,926 records              |

### Geospatial Coverage

| Parameter          | Value                             |
| ------------------ | --------------------------------- |
| **Country**        | Saudi Arabia (KSA)                |
| **City**           | Riyadh (Headquarters)             |
| **Stock Exchange** | Saudi Stock Exchange (Tadawul)    |
| **Currency**       | Saudi Riyal (SAR)                 |
| **Region**         | Middle East & North Africa (MENA) |
| **Time Zone**      | AST (Arabia Standard Time, UTC+3) |

---

## 🔬 Data Provenance

### Source Origin

The primary source of this dataset is **Yahoo Finance (yFinance API)**, which aggregates real-time and historical stock data from:

- **Saudi Stock Exchange (Tadawul)** - Official market data
- **Reuters Financial Data Services**
- **Bloomberg Terminal Data Feeds**

### Data Collection Process

1. **API Query**: Data fetched using yFinance Python library
2. **Ticker**: 1120.SR (AL Rajhi Bank on Saudi Exchange)
3. **Interval**: Daily OHLCV data
4. **Period**: Maximum available historical range

### Transformations Applied

- **Date Formatting**: Standardized to YYYY-MM-DD format
- **Column Reordering**: Structured as Price, Close, High, Low, Open, Volume
- **Missing Values**: Zero-volume days represent market holidays/closures
- **Price Adjustment**: Prices adjusted for stock splits and dividends

---

## 📥 Collection Methodology

### Technical Process

```
1. Python yFinance Library (yf.download)
2. Ticker Symbol: 1120.SR
3. Date Range: Maximum available history
4. Data Format: OHLCV (Open, High, Low, Close, Volume)
5. Export: CSV file format
```

### Data Quality Measures

- **Completeness**: All trading days included; holidays marked with zero volume
- **Accuracy**: Cross-validated with Tadawul official records
- **Consistency**: Uniform date formatting and numeric precision
- **Timeliness**: Data current through December 2025

---

## ⚠️ Challenges & Problems

### 1. Market-Specific Challenges

- **Islamic Calendar Events**: Ramadan, Eid holidays cause trading suspensions
- **Weekend Differences**: Saudi market closed Friday-Saturday (not Saturday-Sunday)
- **Regional Geopolitics**: OPEC decisions, regional tensions affect volatility

### 2. Data Quality Issues

- **Zero Volume Days**: Market closures appear as zero-volume records
- **Price Anomalies**: Some extreme outlier values (40-50 SAR range spikes) need investigation
- **Missing Dividends**: Ex-dividend dates may cause apparent price drops

### 3. Analytical Challenges

- **Currency Considerations**: All prices in SAR; USD conversion requires additional data
- **Market Hours**: Limited trading hours (10:00 AM - 3:00 PM local time)
- **Liquidity Variations**: Volume varies significantly across different periods

### 4. Predictive Modeling Challenges

- **Non-Stationary Data**: Stock prices exhibit trends requiring differencing
- **External Factors**: Oil prices, interest rates, and macroeconomic policies significantly impact banking stocks
- **Black Swan Events**: COVID-19 pandemic (2020), oil price crashes require special handling

---

## 🔗 Data Source

### Official Source

- **Primary**: [Yahoo Finance - AL Rajhi Bank](https://finance.yahoo.com/quote/1120.SR/)
- **Exchange**: [Saudi Stock Exchange (Tadawul)](https://www.saudiexchange.sa/wps/portal/saudiexchange/ourmarkets/main-market)
- **Company Profile**: [AL Rajhi Bank Official Website](https://www.alrajhibank.com.sa/)

### Data Access

```
Ticker: 1120.SR
Market: Tadawul (Saudi Stock Exchange)
Yahoo Finance URL: https://finance.yahoo.com/quote/1120.SR/history/
```

---

## 📈 Problem Development (Step-by-Step)

### Step 1: Market Context (2010-2015)

- Saudi stock market recovery post-2008 financial crisis
- AL Rajhi Bank positioned as leading Islamic finance institution
- Stock price range: ~16-20 SAR
- Gradual market reforms under early Vision 2030 planning

### Step 2: Economic Diversification Era (2015-2018)

- Vision 2030 announced (April 2016)
- Banking sector reforms initiated
- Increased foreign investment allowance
- Stock volatility due to oil price fluctuations

### Step 3: International Market Integration (2018-2020)

- Saudi market inclusion in MSCI Emerging Markets Index (June 2019)
- Increased foreign institutional investment
- Aramco IPO (December 2019) - largest in history
- COVID-19 pandemic impact (March 2020)

### Step 4: Post-Pandemic Recovery (2020-2023)

- Rapid V-shaped recovery in banking sector
- Digital banking transformation acceleration
- Interest rate changes affecting banking profitability
- Continued Vision 2030 implementation

### Step 5: Recent Developments (2023-2025)

- Strong economic growth in Saudi Arabia
- Banking sector consolidation trends
- Increased focus on sustainable finance
- Stock price reaching historical highs (~100 SAR)

---

## 💡 Use Cases

1. **Technical Analysis**: Chart patterns, RSI, MACD, moving averages
2. **Price Prediction**: LSTM, ARIMA, Prophet, XGBoost models
3. **Portfolio Optimization**: Risk-return analysis for MENA portfolios
4. **Market Research**: Middle Eastern banking sector studies
5. **Academic Research**: Emerging market finance, Islamic banking efficiency

---

## 📊 Quick Statistics

| Metric               | Value             |
| -------------------- | ----------------- |
| Minimum Price        | ~14.90 SAR        |
| Maximum Price        | ~100.30 SAR       |
| Average Daily Volume | ~3.5M shares      |
| Maximum Volume       | 18,467,573 shares |
| Total Records        | 3,926             |
| Date Range           | 15+ years         |

---

## 📜 License & Citation

### Suggested Citation

```
AL Rajhi Bank (1120.SR) Historical Stock Data (2010-2025)
Source: Yahoo Finance / Tadawul
Dataset prepared for educational and research purposes
```

### Disclaimer

This dataset is provided for educational, research, and analytical purposes only. It should not be used as the sole basis for investment decisions. Past performance does not guarantee future results.

---

_Last Updated: February 2026_
