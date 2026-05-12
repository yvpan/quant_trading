# Quant Trading Research

A research-oriented quantitative trading repository implementing and evaluating multiple rule-based market-timing and technical-analysis strategies in Python.

The project focuses on systematic strategy development, backtesting, signal generation, and performance evaluation using reproducible notebook-based workflows.

---

## Overview

This repository contains a collection of quantitative trading experiments based on:

- Technical indicators
- Trend-following systems
- Momentum signals
- Volatility-based signals
- Market-timing frameworks
- Walk-forward optimization

The project emphasizes:

- Strategy transparency
- Modular signal design
- Backtesting discipline
- Performance analytics
- Research reproducibility

rather than black-box “price prediction.”

---

## Implemented Strategies

### Dual Moving Average Crossover
Notebook: `dual_moving_average.ipynb`

Implements a classic moving-average crossover strategy using:

- Short-term moving averages
- Long-term moving averages
- Long/flat positioning logic

Used to evaluate medium-term trend-following behavior.

---

### MACD Strategy
Notebook: `MACD.ipynb`

Implements a Moving Average Convergence Divergence (MACD) trading system using:

- MACD line
- Signal line
- Momentum crossover logic

Includes return analysis and portfolio-performance evaluation.

---

### RSI Mean-Reversion Strategy
Notebook: `RSI.ipynb`

Implements a Relative Strength Index (RSI)-based strategy for identifying:

- Overbought conditions
- Oversold conditions
- Mean-reversion opportunities

Explores threshold-based trading logic and signal sensitivity.

---

### Bollinger Band Strategy
Notebook: `bollinger.ipynb`

Implements Bollinger Band trading systems based on:

- Rolling volatility estimation
- Dynamic price bands
- Volatility breakout and reversion behavior

Includes adaptive band-based signal generation.

---

### Trend Following Strategy
Notebook: `trend_following.ipynb`

Implements rule-based trend-following models designed to capture persistent directional market moves using:

- Price momentum
- Trend persistence
- Signal filtering

---

### Market Timing Backtest Framework
Notebook: `market_timing_backtest.ipynb`

A more advanced research framework for:

- Per-stock independent signal generation
- Weighted portfolio construction
- Regime-based analysis
- Walk-forward parameter optimization
- Portfolio-level backtesting

The framework includes examples for:

- Single-stock backtesting
- Signal optimization
- Adaptive Bollinger strategies
- SMA crossover optimization

---

## Key Features

- Multiple technical trading strategies
- Modular signal-generation framework
- Walk-forward optimization workflows
- Portfolio-performance analytics
- Regime-analysis tooling
- Strategy comparison experiments
- Notebook-based research environment
- Transaction-frequency evaluation
- Annualized return and volatility analysis

---

## Performance Metrics

The repository includes utility functions for evaluating:

- Annualized return
- Annualized volatility
- Cumulative return
- Transaction frequency
- Portfolio-equity curves
- Strategy comparison metrics

Example utility functions include:

```python
annual_return()
annual_volatility()
annual_num_transaction()
cum_return()
```

---

## Tech Stack

### Languages
- Python

### Libraries
- NumPy
- pandas
- matplotlib
- seaborn
- TA-Lib

### Quantitative Techniques
- Technical Analysis
- Time-Series Analysis
- Trend Following
- Momentum Strategies
- Mean Reversion
- Volatility-Based Trading
- Walk-Forward Optimization
- Portfolio Backtesting

---

## Repository Structure

```text
quant_trading/
│
├── MACD.ipynb
├── RSI.ipynb
├── bollinger.ipynb
├── dual_moving_average.ipynb
├── trend_following.ipynb
├── market_timing_backtest.ipynb
└── README.md
```

---

## Example Workflow

### Run a notebook locally

```bash
jupyter notebook
```

### Open a strategy notebook

```text
MACD.ipynb
```

### Evaluate strategy performance

The notebooks include:

- Signal generation
- Position construction
- Return calculation
- Performance visualization
- Backtesting evaluation

---

## Research Notes

This repository is intended for quantitative research and educational purposes.

Important limitations include:

- Historical backtests may not generalize to future market regimes
- Transaction costs and slippage may materially affect performance
- Technical indicators are inherently noisy signals
- Parameter overfitting remains a key risk
- Walk-forward validation is necessary for realistic evaluation

The framework is best viewed as an experimental environment for systematic trading research.

---

## Potential Future Improvements

Potential future extensions include:

- Cross-sectional factor models
- Multi-asset portfolio optimization
- Transaction-cost-aware execution modeling
- Bayesian parameter optimization
- Reinforcement learning strategies
- Alternative data integration
- Intraday signal generation
- Transformer-based sequence models
- Live trading interfaces

---

## Disclaimer

This repository is for research and educational purposes only.

Nothing in this repository constitutes financial advice or investment recommendations. Historical backtest results do not guarantee future performance.
