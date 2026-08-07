# Methodology

## Research Question

This study investigates whether changes in ECB policy rates pass through to euro-area non-financial corporation (NFC) lending rates and whether this relationship changed during the monetary tightening cycle beginning in July 2022.

---

## Data

Monthly observations covering January 2003 through March 2026.

Main data sources:

- European Central Bank (ECB) Data Portal
- ECB Monetary Financial Institutions statistics
- Harmonised Index of Consumer Prices (HICP)

---

## Empirical Strategy

The analysis estimates a sequence of distributed-lag Ordinary Least Squares (OLS) regressions.

The baseline specification models monthly changes in NFC lending rates as a function of:

- contemporaneous ECB policy-rate changes
- twelve monthly policy-rate lags

Additional specifications include:

- distributed inflation controls
- post-2022 interaction terms
- Deposit Facility Rate (DFR) robustness checks
- EURIBOR transmission analysis

---

## Statistical Inference

Inference uses Newey-West heteroskedasticity and autocorrelation consistent (HAC) standard errors with twelve lags.

Joint significance is evaluated using Wald tests.

---

## Software

Analysis was performed in:

- R
- R Markdown

Main packages include:

- tidyverse
- lmtest
- sandwich
- modelsummary
- flextable
- ggplot2
