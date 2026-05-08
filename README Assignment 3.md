# R2424224caltonshanji
# Time Series Regime Change Modeling Project

## Overview

This project investigates regime changes in financial markets using a Markov Regime Switching model.

The study analyzes daily returns of the S&P 500 Index to identify transitions between stable and volatile market conditions.

The project was completed using Python in Jupyter Notebook.

---

# Objectives

The objectives of this project are to:

- Model regime changes in financial markets
- Detect shifts between low-volatility and high-volatility periods
- Estimate and interpret model parameters
- Evaluate the effectiveness of the model
- Provide financial insights for investment decision-making

---

# Dataset Information

## Dataset Used
- S&P 500 Index Daily Prices

## Source
- Yahoo Finance

## Frequency
- Daily

## Time Period
- 2017–2025

## Variables
- Date
- Closing Price
- Daily Log Returns

---

# Why This Dataset Was Chosen

The S&P 500 dataset was selected because it contains significant market events and structural changes, including:

- COVID-19 market crash
- Recovery periods
- Inflation shocks
- Interest rate adjustments

These events create distinct market regimes that are suitable for regime-switching analysis.

---

# Model Description

The project uses a Markov Regime Switching model defined as:

y_t = μ_(s_t) + ε_t

Where:

- y_t = observed return at time t
- μ_(s_t) = regime-dependent mean
- s_t = hidden market regime
- ε_t = random error term

The model assumes that markets alternate between:
1. Low-volatility regime
2. High-volatility regime

