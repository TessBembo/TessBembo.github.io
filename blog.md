---
layout: page
title: My Projects
permalink: /blog/
---

<h2 style="text-align: center; margin-top: 20px;">Featured Projects</h2>

<ul>
  <li><a href="/price-simulator/">Regime-Switching Price Simulator</a></li>
  <li><a href="/monte-carlo/">Monte Carlo Behavioral Simulation</a></li>
</ul>

<hr style="border: 1px solid #ffccd5; margin: 40px 0;">

<h2 style="text-align: center; margin-top: 20px;">More Projects</h2>

<ul>
  {% for post in site.posts %}
    {% unless post.title contains "Regime-Switching" or post.title contains "Monte Carlo" %}
      <li style="margin-bottom: 40px; padding-bottom: 20px;">
        <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
        <p>{{ post.excerpt }}</p>
      </li>
    {% endunless %}
  {% endfor %}
</ul>
