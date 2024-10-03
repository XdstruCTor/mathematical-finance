# Geometric Brownian Motion (GBM) Stock Price Simulation

This repository contains Python code that simulates stock price evolution using Geometric Brownian Motion (GBM). The model is widely used in financial mathematics for modeling stock prices and other financial instruments.

## Description

The simulation utilizes the stochastic differential equation (SDE):

\[
dS_t = \mu S_t dt + \sigma S_t dW_t
\]

where:
- \(S_t\) = Stock price at time \(t\)
- \(\mu\) = Drift (expected return)
- \(\sigma\) = Volatility (standard deviation of returns)
- \(W_t\) = Brownian motion

### Parameters
- **Initial stock price (\(S_0\))**: 100
- **Drift (\(\mu\))**: 0.05 (you can adjust this parameter)
- **Volatility (\(\sigma\))**: 0.2 (you can adjust this parameter)
- **Time horizon (\(T\))**: 1.0 (in years)
- **Time increment (\(dt\))**: 0.01 (in years)

## Installation

To run this code, ensure you have Python and the necessary libraries installed. You can install the required libraries using pip:

```bash
pip install numpy matplotlib
