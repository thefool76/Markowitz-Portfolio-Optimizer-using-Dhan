# 📊 Markowitz Portfolio Optimizer using Python + Dhan API

This project implements **Modern Portfolio Theory (MPT)** on live portfolio holdings fetched via the **Dhan API**. It performs 10,000 Monte Carlo simulations to find the most efficient portfolio allocations based on expected return and risk (volatility), and visualizes the **Efficient Frontier** with highlights on:

- ✅ Maximum Sharpe Ratio Portfolio  
- 🛡️ Minimum Volatility Portfolio  

---

## 🚀 Features

- 🔗 **Live data integration** with Dhan trading account using `dhanhq` API
- 📈 Calculation of investment metrics: invested value, market value, gains, return %, allocation %
- 🧮 Simulation of 10,000 random portfolio allocations using `NumPy`
- 🎯 Evaluation of each portfolio’s:
  - Expected return
  - Volatility (risk)
  - Sharpe ratio
- 📊 Visualization of:
  - Portfolio allocation (pie chart)
  - Efficient Frontier (scatter plot)
- 📌 Outputs optimal allocations for both:
  - **Max Sharpe Ratio**
  - **Min Volatility**

---

## 🖼️ Output Visuals

### ✅ Portfolio Allocation Pie Chart
Displays percentage weight of each stock in your portfolio based on market value.

![Portfolio Pie Chart](assets/portfolio_pie.png)<!-- Replace with actual image path -->

### 📈 Efficient Frontier with Max Sharpe & Min Volatility Points
Each dot represents a portfolio simulation. The star markers highlight optimal portfolios.

![Efficient Frontier](assets/efficient_frontier.png) <!-- Replace with actual image path -->

---

## 🛠️ Tech Stack

- Python 3
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib
- DhanHQ API (`pip install dhanhq`)

---

## 🧪 Sample Output


