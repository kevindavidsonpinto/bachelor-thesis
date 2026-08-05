# ECB Interest-Rate Pass-Through During the Post-2022 Tightening Cycle

Bachelor's thesis submitted for the **B.Sc. Economics & Business Economics** programme at **Vrije Universiteit Amsterdam**.

## Overview

This repository contains the complete replication package accompanying my bachelor's thesis on ECB interest-rate pass-through to euro-area non-financial corporation (NFC) lending rates.

The project investigates whether the transmission of ECB policy-rate changes changed during the post-2022 monetary tightening cycle using distributed-lag regression models estimated in R.

---

## Research Question

> Has ECB interest-rate pass-through to euro-area non-financial corporation (NFC) lending rates changed during the post-2022 tightening cycle?

---

## Repository Structure

```
bachelor-thesis/
│
├── thesis/
│   └── Final thesis (PDF)
│
├── code/
│   └── R Markdown replication code
│
├── data/
│   └── Source datasets
│
├── outputs/
│   ├── Figures
│   └── Regression tables
│
└── documentation/
    └── Additional documentation
```

---

## Methodology

The empirical analysis consists of:

- Distributed-lag regression models
- Monthly euro-area data (2003–2026)
- Inflation controls
- Post-2022 interaction effects
- Newey–West HAC standard errors
- Wald tests
- Robustness analyses using the ECB Deposit Facility Rate and EURIBOR

---

## Main Finding

The results indicate that ECB interest-rate pass-through remained substantial following the July 2022 tightening cycle, but the timing of pass-through changed. Immediate pass-through weakened while part of the adjustment shifted towards intermediate horizons.

---

## Software

The analysis was conducted in **R** using packages including:

- tidyverse
- lubridate
- sandwich
- lmtest
- modelsummary
- flextable
- officer

---

## Author

**Kevin Pinto**

Vrije Universiteit Amsterdam

B.Sc. Economics & Business Economics
