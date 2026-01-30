
# Trader Behavior vs Market Sentiment Analysis

## Overview
This project analyzes how trader behavior varies across different market sentiment regimes—Fear, Greed, and Neutral—by combining Bitcoin market sentiment data with historical trade-level data.

## Objectives
- Analyze profitability across sentiment regimes
- Study risk exposure using trade size as a proxy
- Examine Buy vs Sell behavior under Fear and Greed

## Project Structure
ds_harindranath/
├── notebook_1.ipynb
├── notebook_2.ipynb
├── csv_files/
├── outputs/
├── ds_report.pdf
└── README.md


---

## Methodology
1. Validated datasets for null values and datatype consistency
2. Standardized timestamps and aligned both datasets at daily granularity
3. Merged trade-level data with daily market sentiment
4. Performed exploratory data analysis across four dimensions:
   - Profitability
   - Trade size (risk proxy)
   - Risk concentration
   - Directional behavior (Buy vs Sell)

---

## Key Insights
- Median profitability is near zero across all sentiment regimes, indicating a large proportion of breakeven trades
- Average profitability and trading activity increase during Greed periods
- Fear markets exhibit the highest extreme risk concentration, indicating panic-driven behavior
- Traders tend to buy more during Fear and sell more during Greed, suggesting contrarian and profit-taking behavior
- Neutral markets show stable, balanced, and lower-risk trading behavior

---

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Google Colab

---

## Notes
- All analysis was performed in Google Colab
- All notebooks are shared as view-only links
- Outputs and intermediate files are organized according to the required directory structure

