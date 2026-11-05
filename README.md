# price-action-backtester

## What it is

A Python tool that tests a rule-based price-action trading strategy on historical futures data (for example BTC/USDT perpetual on OKX). It takes one strategy written as exact rules, simulates every trade on past candles with realistic fees and slippage, and reports honestly whether the strategy has an edge: number of trades, win rate, average win and loss, drawdown, and how it compares with buy-and-hold and random entries.

## Setup

Requires Python 3.10+.

```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

## Status

Early setup.
