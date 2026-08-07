# Replication Guide

## Requirements

Software

- R (version 4.5 or newer)
- RStudio (recommended)

Required packages

- tidyverse
- ggplot2
- sandwich
- lmtest
- modelsummary
- flextable
- officer
- zoo
- lubridate
- here
- car

---

## Repository Structure

```
code/
data/
outputs/
documentation/
thesis/
```

---

## Running the analysis

1. Clone the repository.

2. Open

```
bachelor-thesis.Rproj
```

3. Open

```
code/thesis_reproduction.Rmd
```

4. Run the document from start to finish.

The script will:

- import the cleaned datasets
- prepare the analysis dataset
- estimate all regression models
- perform robustness checks
- generate figures
- export tables
- save outputs to the `outputs/` directory

---

## Reproducibility

The repository has been organized so that all file paths are relative to the project root using the `here` package.

Running the R Markdown document from the project root should reproduce the complete analysis without modification.
