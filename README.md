# 🧮 Trend Hold Trading Plan Calculator

This web app is designed to help day traders and momentum scalpers using the **Trend Hold Strategy** quickly generate a trading plan with position sizing, risk calculations, and target profit projections.

Built with [Streamlit](https://streamlit.io), it allows for:
- Scaled entries and exits
- Automatic share size based on account size and leverage
- MACD signal detection using live price data
- Chart upload for manual annotation or technical reviews

---

## 📌 Features

- 🔢 **Dynamic Trade Sizing** based on entry prices and account leverage
- 📉 **MACD + EMA Crossover Signal** from recent price data (via Yahoo Finance)
- 💡 **Profit Projections** at three levels: 25%, 25%, and 50% exits
- 📊 **Total Risk Calculation** based on stop loss levels
- 🖼 **Upload Chart Screenshots** for visual reference

---

## 🚀 How to Use

### Option 1: Run Locally
```bash
pip install streamlit pandas yfinance matplotlib
streamlit run trend_hold_calculator.py
```

### Option 2: Deploy to [Streamlit Cloud](https://streamlit.io/cloud)
1. Fork or upload this repo to your GitHub
2. Go to [https://streamlit.io/cloud](https://streamlit.io/cloud)
3. Connect GitHub, select this repo, and deploy the app

---

## 📥 File Overview

| File                     | Description                                  |
|--------------------------|----------------------------------------------|
| `trend_hold_calculator.py` | Main app script built with Streamlit         |
| `requirements.txt`       | Python dependencies                          |
| `README.md`              | You're reading it                            |

---

## 🙋 FAQ

**Q: Can I use this for swing trades or only intraday?**  
A: It’s optimized for intraday 4am–11am setups but can be adapted for multi-day holds.

**Q: How do I pull float or RVOL data?**  
A: The current version uses MACD and EMA signals via Yahoo Finance. Future updates will integrate float/RVOL APIs.

---
