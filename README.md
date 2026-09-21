# Hidden Markov Models for Capturing Uncertainty in Financial Markets

This repository contains the Jupyter notebooks used to produce the figures and empirical results included in the thesis:

**Hidden Markov Models for Capturing Uncertainty in Financial Markets**  
Bachelor's Thesis in Statistics  
Bachelor's Degree in Management Engineering  
Politecnico di Torino  

**Candidate:** Sofia Mirra  
**Supervisor:** Prof. Roberto Fontana  
**Academic year:** 2026

---

## Overview

The thesis investigates how Hidden Markov Models can be used to represent uncertainty in financial markets through latent volatility regimes.

Financial markets often exhibit non-stationary behavior: return distributions change over time, volatility tends to persist in clusters, and extreme events occur more frequently than a static Gaussian model would suggest. The empirical analysis applies a three-state Gaussian Hidden Markov Model to daily S&P 500 log-returns in order to identify low, medium, and high volatility regimes.

This repository provides the computational material used to generate the main figures and empirical outputs of the thesis.

---

## Repository structure

```text
hmm-financial-markets-thesis/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   ├── 01_fig_1_1_prices.ipynb
│   ├── 02_fig_1_2_returns.ipynb
│   ├── 03_fig_1_3_vix_volatility.ipynb
│   ├── 04_fig_1_4_acf_comparison.ipynb
│   ├── 05_fig_1_5_leptokurtosis.ipynb
│   ├── 06_fig_1_6a_order_book.ipynb
│   ├── 07_fig_1_6bc_asset_equity.ipynb
│   ├── 08_fig_2_3_partial_information.ipynb
│   └── 09_hmm_estimation_and_chapter6_figures.ipynb
│
├── figures/
│   └── exported figures used in the thesis
│
└── data/
    └── README.md
