# ESG-Integrated Portfolio Optimization

## Overview

This project demonstrates how Environmental, Social, and Governance (ESG) considerations can be integrated into portfolio optimization. By incorporating ESG factors alongside traditional financial metrics, investors can create portfolios that are both financially sound and socially responsible. The project uses the PyPortfolioOpt library to integrate ESG scores into portfolio optimization and analyzes the results to improve investment strategies.

## Table of Contents

1. Introduction
2. Utilizing PyPortfolioOpt Library
3. Environmental Social Governance (ESG) Metrics as Investment Criteria
4. Visualizing an Efficient Surface in the Risk, Return, and ESG Space
5. Practical Applications of ESG-Integrated Portfolio Optimization

## Key Features

### Introduction
- **Goal:** Integrate ESG considerations into portfolio optimization.
- **Method:** Use PyPortfolioOpt to blend ESG scores with traditional financial metrics for constructing optimized portfolios.

### Utilizing PyPortfolioOpt Library
- **Efficient Frontier Calculation:** Computes the efficient frontier, representing the set of portfolios offering the highest expected return for a given level of risk.
- **Risk Models:** Supports different risk models, including mean-variance optimization, minimum variance, and maximum Sharpe ratio.
- **Asset Allocation:** Determines optimal asset allocation based on various constraints and objectives.
- **Performance Evaluation:** Includes functions to evaluate portfolio performance, such as calculating expected returns, volatility, and Sharpe ratios.

### Environmental Social Governance (ESG) Metrics as Investment Criteria
- **Environmental Criteria:** Evaluates a company’s performance as a steward of nature, including waste management, pollution control, and natural resource conservation.
- **Social Criteria:** Examines how a company manages relationships with employees, suppliers, customers, and communities, including human rights and labor standards.
- **Governance Criteria:** Focuses on a company’s leadership, executive pay, audits, internal controls, and shareholder rights.

### Visualizing an Efficient Surface in the Risk, Return, and ESG Space
- **Simulation:** Visualizes portfolios for different ESG target scores in a 3D space, considering risk, return, and ESG scores.
- **Analysis:** Observes the efficient frontier and surface to identify portfolios that balance risk, return, and ESG considerations.

### Practical Applications of ESG-Integrated Portfolio Optimization
- **Enhanced Portfolio Screening:** Filters out low-performing companies in terms of ESG criteria before performing portfolio optimization.
- **Optimized Weight Allocation:** Adjusts the weights of individual assets based on ESG scores during the optimization process.
- **Setting ESG Constraints:** Sets specific constraints related to ESG performance within the optimization framework.
- **Dual Objective Optimization:** Simultaneously optimizes for financial returns and ESG performance.
- **Dynamic Portfolio Rebalancing:** Guides the dynamic rebalancing of the portfolio based on updated ESG scores and financial metrics.
- **Stress Testing with ESG Scenarios:** Evaluates how the portfolio performs under various ESG-related conditions, ensuring resilience and adaptability.

## Requirements
- Python libraries: yfinance, pandas, numpy, cvxpy, PyPortfolioOpt, matplotlib, seaborn.

This project highlights the integration of ESG considerations into portfolio optimization, offering insights into creating sustainable and socially responsible investment strategies.
