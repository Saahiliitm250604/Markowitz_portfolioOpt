# 📈 Markowitz Portfolio Optimization & Weightage Analysis

This repository contains an in-depth analysis of portfolio optimization using the **Markowitz Efficient Frontier** framework. We use historical NASDAQ stock data to simulate, analyze, and optimize asset weightages, comparing original vs optimized portfolios.

---

## 🔍 Project Overview

The goal of this project is to:

- Apply **Modern Portfolio Theory (MPT)** to historical NASDAQ data
- Construct an **efficient frontier**
- Optimize portfolio allocations to maximize return for a given risk
- Compare **original vs optimized** portfolio weight distributions
- Visualize performance metrics and weight analysis

---

## 📁 Datasets

The project uses the following files:

- `nasdaq_3years_complete_data.csv`:  
  Historical daily price data for NASDAQ stocks over 3 years.

- `Markowitz Portfolio.csv`:  
  Output of Markowitz simulation — returns, risks, Sharpe ratios of various portfolios.

- `Nasdaq_original_weights.csv`:  
  Original portfolio stock weights before optimization.

- `Wightage_Analysis.csv`:  
  Analysis comparing original vs optimized weights for each asset.

---

## ⚙️ Methodology

- **Return Calculation**: Log returns from price data
- **Covariance Matrix**: Risk modeling using asset covariances
- **Random Portfolio Simulation**: Thousands of portfolios simulated to evaluate performance
- **Sharpe Ratio Maximization**: Optimal risk-adjusted return identification
- **Efficient Frontier Construction**: Visualizing trade-offs between return and volatility

---

## 📊 Visualizations

- Risk vs Return scatter plots
- Efficient frontier curve
- Sharpe ratio heatmaps
- Weight distribution bar charts
- Comparative plots of original vs optimized weights

---

## 💾 How to Run

1. **Clone this repo**:
   ```bash
   git clone https://github.com/saahiliitm250604/Markowitz_portfolioOpt.git
   cd Markowitz_portfolioOpt
