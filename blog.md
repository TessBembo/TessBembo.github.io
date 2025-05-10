---
layout: page
title: My Projects
permalink: /blog/
---

## Featured Projects

<ul>
  <li><a href="/projects/price-simulator/">Regime-Switching Price Simulator</a></li>
  <li><a href="/projects/monte-carlo/">Monte Carlo Behavioral Simulation</a></li>
</ul>

## More Projects

<ul>
  {% for post in site.posts %}
    {% unless post.title contains "Regime-Switching" or post.title contains "Monte Carlo" %}
      <li style="margin-bottom: 25px;">
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
      </li>
    {% endunless %}
  {% endfor %}
</ul>
