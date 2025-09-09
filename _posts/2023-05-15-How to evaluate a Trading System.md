---
layout: post
title: How to Really Evaluate a Trading System
subtitle: Moving Beyond Simple Net Profit to the Metrics That Matter
date: 2024-09-09 10:33:32 +0530
categories: [Quant Trading, Strategy, Metrics]
tags: [backtesting, risk management, trading psychology]
---

At first glance, evaluating a trading system looks straightforward: higher net profit = better system, right? Not so fast. That’s actually one of the biggest traps traders fall into.

Net profit alone is like judging a car just by its top speed—you’re ignoring handling, braking, fuel efficiency, and safety. A trading system with a giant profit number could just as easily be a time bomb, waiting to blow up once you factor in risk, commissions, or slippage. 💣

To cut through the noise, let’s break down the real metrics that matter when sizing up a strategy.

### 1. Net Profit ≠ Performance

Net profit tells you what the system brought home during backtests, but it says nothing about risk, stability, or whether those results are repeatable. A system that made $1M ten years ago but lost steadily ever since? Technically “profitable,” but useless in practice.

A solid system shows **consistency**—profits spread evenly across months and years, not one giant outlier trade.

### 2. Average Trade – The First Reality Check

Think of average trade as “profit per trade.” Take net profit and divide by the total number of trades.

- If it’s too small, **commissions and slippage** will eat you alive. 💸
- If it’s healthy and consistent over time, that’s a sign of a real edge.

A good hack: plot average trade as a percentage over time to see whether the system is getting stronger or weaker.

### 3. Win Rate Isn’t Everything

A common rookie obsession: the percentage of profitable trades. Sure, it feels good to be right 70% of the time—but if your winners are tiny and losers are huge, that system will eventually sink.

Instead, pair win rate with the **average win / average loss ratio**:

- A **35% win rate** can still work if winners are 3x bigger than losers (classic trend-following style). 📈
- A **70% win rate** is suspicious if winners barely outpace losers.

The real test? **Mathematical expectancy** = (Win% × Avg Win) – (Loss% × Avg Loss). If this number isn’t positive, the system’s doomed. 💀

### 4. Profit Factor – The Quick Comparison Tool

This is the ratio of gross profit to gross loss.

- **2.0** is generally “healthy.”
- **1.5–3.0** is the usual range for solid systems.
- Anything **over 3.0**? Be skeptical—it might be overfitted.

### 5. Drawdown – The Psychological Killer

Every trader loves equity curves that slope up smoothly. But the real test is how deep the dips go. 

Drawdown shows how much your system loses before bouncing back.

- **10%** = excellent. 👍
- **20–30%** = tolerable but stressful.
- **40–50%** = game over for most people.

And it’s not just the size—it’s the **frequency and distribution**. Occasional dips are fine. A system that constantly plunges underwater? Hard to stomach in real time, even if the backtest says “profitable.” 🌊

### 6. Time in Trades – Portfolio Building

How long a system holds trades matters. If one strategy trades once a week and another scalps 50 times a day, they won’t blend well in a portfolio. Aligning average trade duration helps smooth the equity line when combining strategies.

### 7. Balance Between Long and Short

Good systems don’t just work on one side of the market. If all the profits come from longs (or shorts), that’s a red flag unless there’s a solid reason. 🚩

### The Trader’s Checklist

When evaluating a system, I don’t jump straight to net profit. Instead, I zoom in on:

- The **equity curve** (smooth growth > jagged chaos).
- **Average trade** (must clear costs).
- **Profit factor** (healthy range).
- **Win rate vs. average win/loss balance**.
- **Monthly/annual distribution** (is performance stable?).

A system that passes these checks? Worth testing further. 🧪
