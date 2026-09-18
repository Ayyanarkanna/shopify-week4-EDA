# shopify-week4-EDA

Shopify Stock Visualization, Time-Series Analysis & Financial Insights

Build line plots for OHLC prices and trading volumes over time.

Plot 10-day and 50-day moving averages alongside daily closing prices.

Generate histogram and KDE plots for daily returns to check for normal vs. fat-tailed distributions.

Produce a financial summary report detailing stock stability and high-volatility periods.


**•Shopify Stock**
#•Shopify Stock closing
#•Shopify Stock Volume
#•Shopify Stock Moving
#•Shopify Stock Moving Averages
#•Shopify Daily Returns
#•Shopify 30-Day Rolling

# Shopify (SHOP) Stock Analysis

A data analysis and visualization project focused on tracking, calculating, and interpreting key historical metrics for Shopify Inc. (`NYSE: SHOP`).

---

## Features & Metrics Tracked

* **Shopify Stock Overview:** High-level summary of historical stock data, open-high-low-close (OHLC) values, and price trends.
* **Shopify Stock Closing:** Tracking adjusted and unadjusted daily closing prices to evaluate overall long-term trajectory.
* **Shopify Stock Volume:** Daily trading volume analysis to assess market liquidity, spikes, and investor interest around key events.
* **Shopify Stock Moving:** Price momentum, intraday swings, and direction over designated intervals.
* **Shopify Stock Moving Averages:** Short-term and long-term trend indicators, including:
  * 20-Day Simple Moving Average (SMA)
  * 50-Day Simple Moving Average (SMA)
  * 200-Day Simple Moving Average (SMA)
* **Shopify Daily Returns:** Percentage change calculated day-over-day ($R_t = \frac{P_t - P_{t-1}}{P_{t-1}}$) to measure day-to-day volatility.
* **Shopify 30-Day Rolling:** Rolling metrics over a 30-day window:
  * 30-day rolling mean price
  * 30-day rolling annualized standard deviation (volatility)

---

## Tech Stack

* **Language:** Python 3.9+
* **Data Retrieval:** `yfinance` / Alpha Vantage API
* **Data Processing:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`, `plotly`

---

## Getting Started

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/shopify-stock-analysis.git](https://github.com/your-username/shopify-stock-analysis.git)
cd shopify-stock-analysis
