# Bitcoin Trader Sentiment Analysis

This project analyzes the relationship between Bitcoin trader performance and market sentiment using two datasets:
- `historical_data.csv` – Historical trader-level data from Hyperliquid
- `fear_greed_index.csv` – Daily Bitcoin Fear & Greed sentiment index

---

## Objective

The goal is to uncover how different sentiment phases (Fear, Greed, Extreme Fear, etc.) influence trader behavior, performance, leverage use, and timing — ultimately delivering insights that support smarter trading strategies.

---

## Files

- `DS Task.ipynb` – Jupyter notebook containing all data processing, visualization, and analysis
- `historical_data.csv` – Trader activity and performance dataset
- `fear_greed_index.csv` – Bitcoin sentiment index (daily)
- `README.md` – This file

---

## Requirements

To run this notebook, you’ll need the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
```
---

##  How to Run

1. Clone the repository:
  ```bash
  git clone https://github.com/ShobanaVaishnavi/bitcoin-trader-sentiment-analysis.git
  cd bitcoin-trader-sentiment-analysis
  ```

2. Open and run the notebook:
   ```bash
   jupyter notebook "DS Task.ipynb"
   ```

---

## Key Insights

- **Profitability**: Traders earn the most during *Extreme Greed*. Surprisingly, *Fear* comes next. *Extreme Fear* is the least profitable.
- **Activity**: Trade volume peaks during *Fear* and drops in *Extreme Fear*. *Extreme Greed* also sees reduced activity.
- **Leverage**: Traders use **higher leverage** in *Fear* and *Neutral* markets, contradicting the belief that high leverage is used during bull runs.
- **Next-Day Effect**: Traders perform best the day after *Extreme Greed*, and worst the day after *Extreme Fear*.
- **Sentiment Transitions**: Performance spikes when sentiment deteriorates into *Extreme Fear*, offering high-reward contrarian opportunities.
- **Account Size**:
  - *Small traders* outperform across sentiments, especially in *Neutral* conditions.
  - *Large accounts* thrive during *Extreme Greed*.
  - *Medium accounts* underperform and even lose money during fearful conditions.
- **Optimal Leverage**:
  - Use **2–5x** leverage in *Fear*, *Extreme Fear*, and *Neutral*.
  - Use **50–100x** leverage during *Extreme Greed* for best outcomes (with high risk).

---

## Conclusion

This analysis demonstrates that market sentiment is a powerful predictor of trader performance, but its effects are nuanced. While Extreme Greed offers the highest rewards, it comes with significant risk, whereas Fear phases provide more consistent opportunities. Leverage, account size, and timing further refine these insights into actionable strategies.

---
