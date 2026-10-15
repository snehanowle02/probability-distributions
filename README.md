# AIML Lab – Discrete Probability Distributions

An interactive web app for exploring discrete probability distributions, built for the AIML lab at BMS Institute of Technology and Management.

## Features (Binomial module)
- Inputs for **n** (trials), **p** (success probability) and **k** (target successes), with validation
- Live statistics: mean, variance, standard deviation, second moment E[X²], skewness
- **PMF** calculator: P(X = k) with the substituted formula
- **CDF** calculator: P(X ≤ k) and the complement P(X > k)
- Interactive PMF bar chart that highlights k and marks the mean with a dashed line
- Poisson and Geometric modules are placeholders (coming soon)

## Default check
For n = 20, p = 0.35, k = 7:

| Quantity | Value |
|---|---|
| Mean | 7 |
| Variance | 4.55 |
| P(X = 7) | 0.1844 |
| P(X ≤ 7) | 0.6010 |

## Run
Open `index.html` in a browser. Nothing to install; it needs an internet connection to load the CDN libraries.

## Tech
HTML, Tailwind CSS, Chart.js (+ annotation plugin), KaTeX.

## Author
Sneha Nowle
