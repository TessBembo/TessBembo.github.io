---
layout: page
title: Projects
permalink: /projects/
---

#  Regime-Switching Price Simulator

- [Monte Carlo Behavioral Simulation](/blog/2025/05/07/monte-carlo-meets-psychology)
- [Other cool stuff coming soon!]

  
This project simulates stock price paths using a **Geometric Brownian Motion (GBM)** framework, enhanced with a **regime-switching mechanism** inspired by behavioral finance.

**Standard GBM** assumes that volatility (risk) remains **constant over time.** While mathematically convenient, this assumption does **not reflect real market behavior.** In reality, markets experience distinct phases:

-  **Calm phases:** periods of relatively stable price movements.
-  **Panic phases:** periods of heightened volatility, often triggered by fear, uncertainty, or external shocks (e.g., 2008 crash, COVID-19 crisis).

Behavioral finance research shows that these volatility spikes are not random—they stem from **human psychology,** especially emotions like **fear and herd behavior.**

---

##  Why Build This Model?

This simulator was developed to **bridge the gap between classic quant models and behavioral insight.** While mastering **core quantitative techniques** is essential (e.g., GBM, Monte Carlo methods), it's equally important to recognize their **limitations** and enhance them to **better capture real-world complexity.**

By incorporating **regime-switching volatility:**

-  We introduce a **behaviorally-driven mechanism** that allows the model to dynamically shift between calm and panic states.
-  We make the simulation more **realistic and reflective** of true market dynamics.
-  We demonstrate a commitment to **critically evaluating and improving standard models.**

---

##  How It Works (Conceptually)

The model features two distinct regimes:

| Regime         | Volatility (σ) | Interpretation                                           |
|----------------|----------------|----------------------------------------------------------|
| Calm Market    | 20%            | Regular daily market conditions.                         |
| Panic Market   | 50%            | Fear-driven spikes in volatility (market turmoil).       |

At each time step (e.g., daily), the simulator:

1. **Randomly decides** if the market enters a **panic mode** (e.g., with a 5% probability).
2. If panic is triggered, the model applies the **higher volatility** for that step.
3. The price paths evolve based on the standard GBM formula but with **dynamic volatility.**

This method allows for the emergence of **fat tails** and **volatility clustering,** two critical features observed in empirical market data.

---

##  Why This Matters

By enhancing the standard GBM with behavioral elements, this project achieves:

- **Better realism:** Captures market cycles more accurately.
- **Behavioral integration:** Embeds human psychology (fear-driven volatility) into a quantitative model.
- **Differentiation:** Moves beyond textbook implementations to develop a model that reflects **real-world phenomena.**

---

> *This project is part of a broader effort to combine rigorous quantitative modeling with insights from psychology and behavioral economics, aiming to create simulations that capture not only mathematical structure but also human-driven market behavior.*

