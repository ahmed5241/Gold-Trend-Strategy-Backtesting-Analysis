# 🥇 Gold Trend Strategy & Backtesting Analysis

## 📌 Project Overview

This project analyzes historical gold prices over the last 10 years to identify optimal buying opportunities using data-driven investment strategies.

The goal is to replace emotional decision-making with quantitative analysis by detecting market trends and testing a systematic gold-buying strategy.

---

## 🎯 Business Problem

Gold investors often struggle to decide **when to buy** due to daily price fluctuations and market uncertainty.

This project answers:

* When is gold entering a strong upward trend?
* Can a rule-based strategy outperform simply buying and holding gold?
* How much risk can be reduced using trend analysis?

---

## 🧠 Strategy Idea

The project applies a **Trend-Following Strategy** based on Moving Averages:

* **MA50** → Short-term market trend
* **MA200** → Long-term market trend

### Decision Rule:

* ✅ Buy when MA50 > MA200 (Uptrend)
* ⏸ Stay out when MA50 ≤ MA200

This allows investment only during strong market momentum.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* yFinance API
* Jupyter Notebook

---

## 📊 Analysis Steps

1. Data collection using Yahoo Finance API
2. Data cleaning & preparation
3. Feature engineering (Moving Averages)
4. Buy/Sell signal generation
5. Strategy backtesting
6. Risk analysis (Max Drawdown)
7. Performance comparison vs Buy & Hold

---

## 📈 Key Metrics

* Market Return vs Strategy Return
* Time invested in market
* Buy signal detection
* Maximum Drawdown (Risk Measurement)

---

## 📉 Results

The strategy demonstrates how trend-based investing can:

* Reduce exposure during market downturns
* Improve risk management
* Provide structured investment decisions

---

## 💡 Business Insights

* Gold performs best during sustained trends rather than short-term volatility.
* Data-driven timing can reduce emotional investing decisions.
* Trend confirmation improves entry timing.

---

## 📂 Project Structure

```
Gold_Backtest_Project/
│
├── data/
│   └── gold_final_analysis.csv
│
├── notebooks/
│   └── gold_analysis.ipynb
│
└── README.md
```

---

## 🚀 Future Improvements

* Add machine learning price prediction
* Build Power BI dashboard
* Real-time gold price monitoring
* Trading signal automation

---

## 👨‍💻 Author

Ahmed Henedy
Aspiring Data Analyst | Finance & Gold Market Enthusiast
 
