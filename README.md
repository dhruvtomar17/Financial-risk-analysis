Quantitative Finance & Risk Management Suite 
Author: Dhruv tomar

Objective: A data-driven framework for measuring asset-level risk and optimizing multi-sector portfolio allocation using Python and Modern Portfolio Theory.

Project Overview
This repository contains two integrated projects that bridge the gap between theoretical mathematics and real-world financial decision-making.

Market Risk Diagnostic (VaR & Volatility) Problem: Standard financial models often underestimate the risk of "Black Swan" events or high-volatility periods in the Indian market.

Action: Conducted a deep dive into Value at Risk (VaR) for high-weight index constituents (e.g., Reliance, Nifty 50).

Technicals: Used Historical Simulation and Monte Carlo methods to calculate the potential maximum loss at a 95% confidence interval.

Key Insight: Discovered that empirical data often exhibits "Fat Tails," meaning extreme market moves happen more frequently than a standard Bell Curve (Normal Distribution) predicts.

Multi-Asset Portfolio Optimizer (The Efficient Frontier) Problem: How do you maximize returns while minimizing the "bumpiness" (volatility) of a portfolio?

Action: Built a diversified basket of 5 stocks across different sectors (Banking, Tech, Energy, FMCG, and Index ETFs).

Technicals: * Developed an Annualized Covariance Matrix to map how different sectors move in relation to one another.

Simulated 10,000 portfolios via Monte Carlo to identify the Maximum Sharpe Ratio.

The "Analyst" Edge: Implemented Weight Constraints (Capping any single asset at 35%).

Key Insight: Demonstrated that while an unconstrained model might "chase" a single winning stock (e.g., HDFC Bank), a constrained model provides a more resilient, defensible strategy for institutional fund management.

Tech Stack & Methodology:-

Language: Python 3.x

Libraries: Pandas (Data Manipulation), NumPy (Linear Algebra & Matrix Operations), yfinance (Market Data), Matplotlib (Visualization).

Mathematical Concepts: Log Returns, Covariance Matrices, Geometric Brownian Motion, Monte Carlo Simulations, and Risk-Adjusted Return (Sharpe Ratio).

Repository Structure:-

Project_1_Risk_Diagnostics/: Notebooks focusing on single-asset volatility and VaR.

Project_2_Portfolio_Optimization/: Notebooks focusing on MPT and the Efficient Frontier.
