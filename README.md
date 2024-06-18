# Bayesian hierarchical modelling of noisy gamma processes
[![DOI](https://zenodo.org/badge/814873237.svg)](https://zenodo.org/doi/10.5281/zenodo.11900590)

This repository contains tex, code, and online appendix for

Leadbetter, R., Caceres, G. G., & Phatak, A. (2024). Bayesian Hierarchical Modelling of Noisy Gamma Processes: Model Formulation, Identifiability, Model Fitting, and Extensions to Unit-to-Unit Variability. [ArXiv. /abs/2406.11216](https://arxiv.org/abs/2406.11216)

## Guide to repository

**R/** Contains all code necessary to reproduce the main analysis. The `.qmd` files are [Quarto](https://quarto.org/) documents with embedded `R` code and can be compiled by installing Quarto and R and running `quarto render supplementary-material-1.qmd` from the command line or by using [RStudio](https://quarto.org/docs/get-started/hello/rstudio.html).

**figures/** All figures used to generate the main manuscript (generated by `.qmd` files).

**paper/** All `.tex` code to generate the article in an arXiv template.

**tables/** All tables used to generate the main manuscript in a LaTeX format (generated by `.qmd` files).
