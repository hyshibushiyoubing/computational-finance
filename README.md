## 📘 Project Overview

This project is a final take-home group assignment for QF627: Programming and Computational Finance. The objective is to develop and backtest trading strategies using historical S&P 500 data (via the SPY ETF) over the 20-year period from November 2005 to October 2024.

### 🎯 Goal
Design strategies that outperform the S&P 500 using only $100,000 in starting capital per strategy, without borrowing or using composite assets.

### 🧩 Core Tasks

#### Part 1: Strategy Design
Develop strategies using:
- Momentum-based methods
- Mean-reversion techniques
- Machine learning approaches

#### Part 2: Backtesting & Metrics
Backtest each strategy and compare performance based on:
- Sharpe Ratio
- Compound Annual Growth Rate (CAGR)
- Maximum Drawdown
- Ending account value

#### Part 3: Executive Summary
Summarize and compare at least the top 3 strategies using metrics above, and bookmark results clearly in the notebook.

#### Part 4: Self-Critique
Critically analyze potential issues in your approach:
- Survivorship Bias
- Lookahead Bias
- Market Regime Shifts

Discuss how these could have affected results and how your team mitigated them.

### 📊 Evaluation

- 28 points: Programming + analysis quality across the 4 core parts
- 12 points: Based on your strategy’s performance vs. others (cumulative return)

### ✅ Notes

- Backtest using the **last 20%** of the data
- Build models using the **first 80%**
- Use only `SPY` data (no sub-indexes or leverage)
