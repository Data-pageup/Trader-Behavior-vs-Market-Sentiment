#   Trader Behavior vs Market Sentiment

**By** Amirtha Ganesh R 
**Date:** December 2025

 

## 🔗 Google Colab Notebook

**Main Analysis Notebook:**  
[https://colab.research.google.com/drive/14tb6KqEB8ijX3mXJUUKfoLAGxHqsLSlU?usp=sharing]

**Access:** Set to "Anyone with the link can view"

## 📊 Analysis Summary

This project analyzes the relationship between trader behavior (profitability, risk-taking, volume) and market sentiment (Fear/Greed) using:

- **Historical Trader Data** from Hyperliquid (211,224 trades)
- **Bitcoin Fear & Greed Index** (2,644 daily sentiment labels)

### Key Findings:
1. **Fear periods** generate 2.5× higher daily PnL despite lower activity
2. **Greed periods** show 87% higher risk ratios but lower efficiency
3. **Neutral conditions** yield highest PnL per trade (63.82 USD)
4. Top 10% of traders capture 63% of profits during Fear vs 58% during Greed

## 🛠️ Technologies Used

- **Python 3.12** (Google Colab)
- **Pandas, NumPy** - Data processing
- **Matplotlib, Seaborn** - Visualizations
- **Statistical Analysis** - Sentiment comparison, quintile analysis

## 📝 Datasets

1. **Fear & Greed Index:** Daily Bitcoin sentiment classifications
2. **Hyperliquid Trader Data:** Trade-level execution records (May 2023 - May 2025)

## 📄 Report

The `ds_report.pdf` contains:
- Data preparation methodology
- Comprehensive statistical analysis
- Actionable trading insights
- Limitations and future work

---

 **Contact:** amirthaganeshramesh@gmail.com / +91 6374707500
