# Mutual_Fund
# Mutual Fund Investment Plan using Python

## Project Overview
The **Mutual Fund Investment Plan using Python** project focuses on building a Python-based investment analysis tool that helps investors create and evaluate diversified mutual fund portfolios.

The objective of this project is to analyze historical mutual fund performance, calculate investment KPIs, evaluate portfolio risk and returns, and generate insights that help investors make better financial decisions.

This project will involve **data collection, portfolio construction, risk-return analysis, simulation, visualization, and portfolio optimization** using Python.

---

## Business Problem
Investors often struggle to choose the right mutual fund portfolio while balancing **risk and returns**. Selecting the wrong allocation can lead to poor returns or higher financial risk.

This project aims to answer the following business question:

> **How can investors build a diversified mutual fund portfolio that maximizes returns while managing risk effectively?**

---

## Project Objectives
The main objectives of this project are:

- Collect and analyze historical mutual fund performance data
- Measure returns and investment risks
- Build diversified mutual fund portfolios
- Simulate portfolio performance under different scenarios
- Calculate risk-adjusted metrics such as Sharpe Ratio and Sortino Ratio
- Generate visual insights for investment decision-making
- Recommend optimal portfolio allocation based on risk tolerance

---

## Project Workflow

### Phase 1: Data Collection & Preparation
In this phase, historical mutual fund data will be collected and prepared for analysis.

#### Tasks:
- Collect mutual fund historical data
- Gather:
  - NAV (Net Asset Value)
  - Historical returns
  - Expense ratio
  - Dividend information
- Handle missing values
- Remove inconsistencies and outliers
- Standardize time intervals (monthly/quarterly)

#### Tools & Libraries:
- Pandas
- NumPy
- yFinance
- Requests API

---

### Phase 2: Exploratory Data Analysis (EDA)
This stage focuses on understanding fund performance trends and patterns.

#### Analysis Includes:
- Fund performance trends
- Return distribution
- Volatility analysis
- Expense ratio comparison
- Correlation between funds

#### Visualizations:
- Line Charts
- Histograms
- Boxplots
- Heatmaps

#### Libraries:
- Matplotlib
- Seaborn
- Plotly

---

### Phase 3: Portfolio Construction
This phase focuses on creating diversified investment portfolios.

#### Features:
- User-defined allocation percentage
- Multi-fund investment portfolio
- Diversification strategy
- Historical portfolio performance tracking

Example:

| Fund | Allocation |
|------|------------|
| Fund A | 60% |
| Fund B | 40% |

---

### Phase 4: Risk & Return Analysis
This stage evaluates investment performance using financial KPIs.

#### KPIs:
- Total Return
- Annualized Return
- CAGR
- Standard Deviation (Volatility)
- Sharpe Ratio
- Sortino Ratio

#### Goal:
Measure portfolio risk and identify risk-adjusted performance.

---

### Phase 5: Monte Carlo Simulation
Monte Carlo simulation will be used to estimate future portfolio performance under different market conditions.

#### Purpose:
- Forecast possible portfolio outcomes
- Estimate return variability
- Analyze uncertainty in investment returns

---

### Phase 6: Data Visualization & Dashboard
Interactive visualizations will be developed to improve user understanding.

#### Dashboard Features:
- Portfolio performance trends
- Risk vs Return scatter plots
- Portfolio allocation pie charts
- Benchmark comparison
- Heatmaps for fund performance

#### Tools:
- Streamlit / Dash
- Plotly
- Matplotlib

---

### Phase 7: Portfolio Optimization
Optimization techniques will be implemented to suggest better fund allocations.

#### Techniques:
- Mean-Variance Optimization
- Risk-return balancing
- Allocation sensitivity analysis

---

## Tech Stack

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- SciPy
- yFinance
- Streamlit

---

## Expected Outcomes
By the end of this project, the system will be able to:

✔ Analyze mutual fund historical performance  
✔ Measure portfolio risk and returns  
✔ Simulate investment performance  
✔ Recommend diversified portfolio allocations  
✔ Generate interactive investment visualizations  
✔ Help investors make data-driven decisions

---

## Folder Structure

```bash
Mutual-Fund-Investment-Plan/
│── data/
│── notebooks/
│── src/
│── visualizations/
│── dashboard/
│── README.md
│── requirements.txt
```

---

## Current Project Status
🚧 **Project in Progress**

Currently working on:

✅ Project Planning  
⬜ Data Collection  
⬜ Data Cleaning  
⬜ Exploratory Data Analysis  
⬜ Portfolio Construction  
⬜ Risk & Return Analysis  
⬜ Monte Carlo Simulation  
⬜ Dashboard Development  
⬜ Portfolio Optimization

---

## Future Enhancements
- Real-time mutual fund tracking
- Personalized investment recommendations
- SIP planning module
- Tax-saving investment analysis
- Mobile-friendly dashboard

---

## Author
**Vidhya Thennarasu**

Aspiring Data Analyst | Python | SQL | Power BI | Excel
