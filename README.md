# 📈 Trading Behavior & Market Sentiment Analysis

## Overview

This project investigates the relationship between cryptocurrency trader behavior on the Hyperliquid exchange and Bitcoin market sentiment using the Fear & Greed Index.

The objective was to determine how market emotions influence trading profitability, win rates, trade volume, and overall trading performance.

---

## Datasets Used

### Bitcoin Fear & Greed Index

- Extreme Fear
- Fear
- Neutral
- Greed
- Extreme Greed

### Hyperliquid Historical Trading Data

Contains:

- Account Information
- Trading Symbol
- Execution Price
- Position Size
- Trade Direction
- Timestamp
- Leverage
- Closed Profit & Loss (PnL)

---

## Objectives

- Analyze how market sentiment affects trading profitability.
- Compare win rates across sentiment categories.
- Study trading volume behavior under different market emotions.
- Validate findings using statistical testing.
- Generate actionable trading and risk management insights.

---

## Methodology

### 1. Data Cleaning & Preprocessing

- Standardized timestamps and date formats.
- Converted PnL and volume fields into numerical values.
- Aligned trading records with sentiment data.
- Handled missing and inconsistent values.

### 2. Data Integration

- Merged trader activity with daily Fear & Greed Index values.
- Created a unified dataset for sentiment-based performance analysis.

### 3. Exploratory Data Analysis

Performed analysis on:

- Sentiment Distribution
- Profitability by Sentiment
- Trading Volume Patterns
- Win Rate Comparison

### 4. Statistical Testing

- Applied Kruskal-Wallis Test
- Verified statistical significance of profitability differences

---

## Key Findings

| Metric | Result |
|----------|----------|
| Most Profitable Sentiment | Extreme Greed |
| Average PnL | $67.89 |
| Least Profitable Sentiment | Neutral |
| Average PnL | $34.31 |
| Highest Win Rate | Extreme Greed (52%) |
| Lowest Win Rate | Extreme Fear (37%) |
| Statistical Significance | p-value = 0.0000 |

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Colab

---

## Business Impact

This analysis demonstrates how sentiment-driven insights can support:

- Algorithmic Trading Systems
- Portfolio Risk Management
- Dynamic Position Sizing
- Trading Strategy Optimization
- Market Timing Decisions

---

## Author

**Pranjal Mankar**

- GitHub: https://github.com/pranjalmankar2004
- LinkedIn: https://linkedin.com/in/pranjal-mankar
