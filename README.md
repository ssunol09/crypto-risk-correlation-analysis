# Crypto Risk & Correlation Analysis: BTC, ETH, SOL

## Overview
This project analyzes the risk, volatility, correlation, beta, and regime behavior of BTC, ETH, and SOL using Python and Jupyter Notebook.

The goal is to understand how crypto assets behave individually and collectively across **calm** vs **stress** market environments, and to evaluate whether diversification benefits persist during tail events.

---

## Key Findings

- **BTC is the anchor asset** — lowest volatility & shallowest drawdowns  
- **ETH behaves like high-beta BTC** — tighter correlation, stronger moves  
- **SOL is extremely high beta** — highest volatility and deepest drawdowns  
- **Correlations spike during crashes** — diversification collapses  
- **Market dominated by one risk factor** — BTC drives most of the movement  

These patterns reflect institutional risk assumptions:  
crypto behaves like a single **“BTC beta”** factor during stress.

---

## Tech Stack

- Python  
- pandas / numpy  
- matplotlib  
- yfinance  
- Jupyter Notebook  

---

## Project Structure

```
crypto-risk-correlation-analysis/
│
├── notebooks/              # Full Jupyter analysis
├── reports/                # HTML + PDF export
├── figures/                # High-resolution charts
└── README.md
```


## Full Report

📄 **[01_crypto_risk_correlation.pdf](reports/01_crypto_risk_correlation.pdf)**  
13-page institutional-style quantitative research report.

---

## What I Learned

- Building an end-to-end quantitative research pipeline  
- Computing returns, volatility, Sharpe ratios, drawdowns  
- Rolling volatility / rolling correlation  
- Beta estimation and regression visualization  
- Regime segmentation (calm vs stress)  
- Crypto’s factor structure and correlation breakdowns  

---

## Next Steps

- Add ETH/SOL regime beta comparison  
- Add a cross-asset benchmark (BTC vs Gold or BTC vs SP500)  
- Expand analysis to include a DeFi token or L2 network  
