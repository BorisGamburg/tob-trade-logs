# TOB — Automated Crypto Trading System

TOB is an independently developed, modular trading system for cryptocurrency futures on Bybit.

The system is deployed and operates on the live exchange under real market conditions. This repository is intended to provide operational log snapshots that illustrate the system's actual trading processes.

## System overview

TOB implements multiple trading strategies, including:

- **GridMTF** — a multi-timeframe grid strategy with automated position management, rearming, and configurable exit conditions.
- **Hedge2** — a strategy for managing opposing positions and position recovery.

The system integrates exchange communication, order execution, position management, trade accounting, and PostgreSQL storage.

## Operational log snapshots

Published log samples can illustrate:

- Strategy decisions and exit signals.
- Order placement and execution.
- Position and stack-level updates.
- Trade accounting and automatic rearming.

These are static snapshots. They may not reflect the system's current state and are not a real-time feed.

## Source code

The source code is available in the main repository:

[**BorisGamburg/tb — Source Code**](https://github.com/BorisGamburg/tb)

TOB is an ongoing software development project. These logs are provided for technical inspection and do not imply any guarantee of trading performance or profitability.
