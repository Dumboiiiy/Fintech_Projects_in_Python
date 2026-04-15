# Fintech Projects in Python

This repository contains three Python-based financial automation scripts designed to streamline portfolio construction and stock analysis. These projects utilize data-driven methodologies to implement various investment strategies, ranging from simple capital allocation to complex multi-factor scoring.

---

## Projects Overview

### 1. Equal Weights Strategy
This project automates the process of capital allocation for a predefined list of stocks. It takes a target portfolio value (e.g., 1,000,000 INR) and calculates the exact number of shares to purchase for each ticker to ensure an equal monetary distribution across the entire selection.

### 2. Value Investing Strategy
This project focuses on identifying "undervalued" stocks by analyzing key fundamental metrics. The script evaluates companies based on P/E ratio, P/B ratio, Price-to-Sales ratio, and Enterprise Value metrics. It uses a percentile-based scoring system to rank stocks and identify the top 10 candidates for a value-oriented portfolio.

### 3. Dividend Based Investing
This project focuses on income generation by identifying stocks with robust dividend performance. It employs a weighted scoring model that analyzes dividend yield, dividend rate, payout ratio, and 5-year average dividend yields to rank stocks for an income-focused portfolio.

---

## Technical Stack
* **Language:** Python 3
* **Libraries:** Pandas, NumPy
* **Financial Data:** Yahoo Finance 
