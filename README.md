# Trader Performance Analysis Based on Market Sentiment

## Overview

This project explores the relationship between market sentiment—categorized as **Fear** or **Greed**—and the performance of traders using real trading data from the **Hyperliquid** platform. By combining sentiment analysis with historical trader activity, we aim to uncover behavioral patterns and develop actionable insights to support smarter trading strategies.

## Datasets Used

### 1. Bitcoin Market Sentiment Dataset
- **Columns**: `Date`, `Classification (Fear/Greed)`
- Describes the psychological state of the market on each day.

### 2. Historical Trader Data from Hyperliquid
- **Columns** (selected): `account`, `symbol`, `execution price`, `size`, `side`, `time`, `start position`, `event`, `closedPnL`, `leverage`, etc.
- Captures trade-level details for each trader across various market conditions.

## Objectives

- Correlate trader performance with market sentiment.
- Identify patterns in trading behavior during periods of fear and greed.
- Assess how factors like leverage, position size, and trade side impact profitability under different sentiment conditions.
- Provide insights to improve trading strategies and risk management.

## Project Structure

```bash
.
├── data/
│   ├── bitcoin_market_sentiment.csv
│   └── hyperliquid_trader_data.csv
├── notebooks/
│   └── analysis.ipynb
├── outputs/
│   ├── plots/
│   └── results/
├── README.md
└── requirements.txt
