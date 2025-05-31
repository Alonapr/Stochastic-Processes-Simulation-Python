# Stochastic-Processes-Simulation-Python

This repository contains three lab works from the course on Stochastic Processes and Simulation Modeling in National Taras-Shevchenko-University Kyiv. All tasks are implemented in Python and demonstrate simulation of random variables, analysis of stochastic processes, and stock price modeling using different mathematical approaches.

## Lab 1 — Distribution Modeling
- Generation of random sequences (n = 10000) with specified distributions:
  - Normal (`random.gauss()`, `random.normalvariate()`)
  - Pareto (`random.paretovariate()`)
  - Weibull (`random.weibullvariate()`)
  - Gamma (`random.gammavariate()`)
  - Uniform (`random.random()`)
- Inverse transform method for Normal and Pareto distributions.
- Estimation of mathematical expectation and variance.
- Distribution hypothesis testing.
- Comparison with theoretical distributions.

## Lab 2 — Wiener Process Simulation
- Generation of Wiener process using different trigonometric series.
- Visualization of single and multiple realizations.
- Analysis of mean and variance for multiple trajectories.
- Normality testing of increments (e.g., using Shapiro–Wilk test).
- Modeling volatility in the Heston stochastic model.

## Lab 3 — Stock Price Modeling
- Simulation of stock price under stochastic volatility (Heston model).
- Comparison of two simulation methods for asset prices.
- Analysis of result accuracy and graphical visualization.

## Tools
- Python 3
- Libraries: `random`, `numpy`, `matplotlib.pyplot`, `scipy.stats`
