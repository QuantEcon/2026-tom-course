# Tom's Course 2026

This repository contains lecture materials for Tom's 2026 course on quantitative economic modeling.

## Lectures

### Lecture 1: Asset Pricing
- Asset Pricing: Finite State Models
- Asset Pricing II: The Lucas Model

### Lectures 2-6: Beliefs and Financial Markets
- Statistical Divergence Measures
- Likelihood Ratio Processes
- Competitive Equilibria with Arrow Securities
- Heterogeneous Beliefs and Financial Markets
- Heterogeneous Beliefs and Bubbles
- Speculative Trading with Bayesian Learning

## Building the Book

To build the Jupyter Book locally:

```bash
conda env create -f environment.yml
conda activate quantecon
cd lectures
jupyter-book build .
```

The HTML output will be in `lectures/_build/html/`.

## Source

These lectures are sourced from:
- [Intermediate Quantitative Economics with Python](https://python.quantecon.org/)
- [Advanced Quantitative Economics with Python](https://python-advanced.quantecon.org/)
