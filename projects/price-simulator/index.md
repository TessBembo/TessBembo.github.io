---
layout: page
title: Regime-Switching Price Simulator
permalink: /projects/price-simulator/
---

# 🎢 Regime-Switching Price Simulator

- [Monte Carlo Behavioral Simulation](/projects/monte-carlo/)
- [Regime-Switching Price Simulator](/projects/price-simulator/)
- [Other cool stuff coming soon!]

This project simulates stock price paths using a <strong style="color:#e91e63;">Geometric Brownian Motion (GBM)</strong> framework, enhanced with a <strong style="color:#e91e63;">regime-switching mechanism</strong> inspired by behavioral finance.

**Standard GBM** assumes volatility (risk) stays <strong style="color:#e91e63;">constant over time.</strong> That’s clean math—but let’s be real, it’s not how markets behave. In reality, things get messy, and markets flip between phases:

- <strong style="color:#e91e63;">Calm phases:</strong> periods of relatively stable price movement.
- <strong style="color:#e91e63;">Panic phases:</strong> sudden spikes in volatility, often triggered by fear, uncertainty, or external shocks (think: 2008 crash, COVID-19 chaos).

Behavioral finance tells us these volatility bursts aren’t random—they’re driven by <strong style="color:#e91e63;">human psychology</strong>, especially emotions like <strong style="color:#e91e63;">fear and herd behavior.</strong>

---

## 🚀 Why Build This Model?

I built this to <strong style="color:#e91e63;">bridge the gap</strong> between classic quant models and behavioral insights. Sure, mastering <strong style="color:#e91e63;">core quantitative tools</strong> (GBM, Monte Carlo) is crucial, but I also want to push deeper—recognizing their <strong style="color:#e91e63;">limitations</strong> and making them <strong style="color:#e91e63;">better reflect real-world complexity.</strong>

By weaving in <strong style="color:#e91e63;">regime-switching volatility:</strong>

- I added a <strong style="color:#e91e63;">behaviorally-driven mechanism</strong> that lets the model switch between calm and panic in real time.
- The simulation becomes more <strong style="color:#e91e63;">realistic and reflective</strong> of actual market dynamics.
- It’s part of my commitment to <strong style="color:#e91e63;">critically evaluating and improving</strong> traditional models.

---

## 🛠️ How It Works (Conceptually)

The model runs on two key regimes:

| Regime         | Volatility (σ) | What It Means                                           |
|----------------|----------------|---------------------------------------------------------|
| Calm Market    | 20%            | Regular, stable market vibes.                            |
| Panic Market   | 50%            | High-alert mode—volatility spikes driven by fear.        |

At each time step:

1. The simulator <strong style="color:#e91e63;">randomly decides</strong> if we enter panic mode (e.g., ~5% probability).
2. If panic hits, the model applies <strong style="color:#e91e63;">higher volatility</strong> for that period.
3. Price paths evolve using GBM—but now with <strong style="color:#e91e63;">dynamic volatility.</strong>

This design naturally produces <strong style="color:#e91e63;">fat tails</strong> and <strong style="color:#e91e63;">volatility clustering</strong>—two must-have features that real markets show.

---

## 💡 Why It Matters

This upgraded GBM brings:

- <strong style="color:#e91e63;">Better realism:</strong> Captures the emotional swings of real markets.
- <strong style="color:#e91e63;">Behavioral integration:</strong> Weaves human psychology (fear, uncertainty) into the math.
- <strong style="color:#e91e63;">A personal edge:</strong> Pushes beyond textbook models to create something sharper—and closer to how the real world actually works.
