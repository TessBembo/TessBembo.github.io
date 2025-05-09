---
layout: page
title: Projects
permalink: /projects/
---

## My Current Projects

- [Monte Carlo Behavioral Simulation](/blog/2025/05/07/monte-carlo-meets-psychology)
- [Other cool stuff coming soon!]


Most Monte Carlo simulations focus on generating random samples based on known distributions—whether it's stock price paths, risk factor spreads, or weather predictions. These models are powerful and widely used in quantitative finance and risk management, but I found myself wondering: **are we truly modeling *real* uncertainty, or just mathematical neatness?**

In my latest project, I built a Monte Carlo simulation with an extra twist: rather than simply plugging in static assumptions, I layered in **behaviorally-driven randomness** to better reflect the **messy human dynamics** that influence markets and decisions.

### Why Does This Matter?

In real life, variables aren't just randomly distributed—they’re often shaped by **human behavior, biases, and systemic reactions.** For example:

- Investors **overreact** to losses, leading to volatility clustering.  
- Consumers' decisions **shift** based on peer effects or sentiment swings.  
- Risk assessments **change dynamically** based on evolving news or shocks.

By integrating *stochastic behavior patterns* into my Monte Carlo, I aim to model a world that’s closer to how people *actually* behave—not just how we wish they did in tidy math equations.

### What Makes This Monte Carlo Different?

 I introduced **adaptive parameters** that allow the model to shift based on prior outcomes (e.g., reinforcing or dampening cycles).  
 I tested **non-linear randomness** that creates "fat tails" and higher-order risk, which are typical in real-world systems but often overlooked.  
 I focused on **context-sensitive randomness:** randomness that changes depending on the *state of the system* (not just uniform noise).

### The Big Takeaway

My rationale is simple: if we're using simulations to *forecast real-world outcomes,* our models should reflect not just mechanical randomness but the **behavioral uncertainty** that defines human systems. This project is a first step in that direction, and I'm excited to refine it further as my skills in mathematics and psychology continue to grow.

## Simulation Results

![Graph 1](/assetsimgmonte-carlo-graph1.png.png)

![Graph 2](/assetsimgmonte-carlo-graph2.png.png)

![Graph 3](/assetsimgmonte-carlo-graph3.png.png)

---

*Check out the code [on GitHub](https://github.com/yourrepo) or see related posts in my [Projects](/projects) page.*
