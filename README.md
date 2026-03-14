# Trading Sentiment Analysis

Analysis of the relationship between Bitcoin market sentiment and trader performance using data from Hyperliquid and the Fear & Greed Index.

---

## Overview

This project explores whether market sentiment (**Fear vs Greed**) has a measurable impact on how profitably traders perform. By merging historical trade data with daily sentiment scores, we identify patterns that could inform smarter trading decisions.

---

## Datasets

| File | Description |
|------|-------------|
| `historical_data.csv` | Trade records from Hyperliquid (211,000+ trades, 2023–2025) |
| `fear_greed_index.csv` | Daily Bitcoin Fear & Greed Index scores (2018–2025) |

---

## Project Structure

```
trading-sentiment-analysis/
├── main.ipynb              # Main analysis notebook
├── historical_data.csv     # Hyperliquid trader data
├── fear_greed_index.csv    # Bitcoin Fear & Greed Index
├── requirements.txt        # Python dependencies
└── README.md
```

---

## What's Inside the Notebook

1. Import Libraries  
2. Load Datasets  
3. Data Cleaning & Preprocessing  
4. Sentiment Distribution  
5. Profitability vs Market Sentiment  
6. BUY vs SELL Performance by Sentiment  
7. Trade Profit & Loss Distribution  
8. Fear/Greed Score vs Daily PnL (Correlation)  
9. Top Performing Traders  
10. Trader Performance by Sentiment (Heatmap)  
11. Profitability by Coin  
12. Trading Activity by Sentiment  
13. Key Insights  
14. Strategy Recommendations  

---

## Key Findings

- Sentiment directly affects **average PnL per trade** across all sentiment regimes  
- Fear periods are **not always unprofitable** — some traders buy dips effectively  
- **BUY trades outperform during Fear**, while **SELL trades gain an edge during Greed**  
- Profits are concentrated among a **small group of consistently skilled traders**  
- The Fear/Greed numeric score shows a **measurable correlation with daily win rate**

---

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Shubham-kumar1-hub/trading-sentiment-analysis.git
cd trading-sentiment-analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Open the notebook

```bash
jupyter notebook main.ipynb
```

---

## Requirements

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

---

## Author

**Shubham Kumar**

GitHub:  
https://github.com/Shubham-kumar1-hub
