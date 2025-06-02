# Visualizing Statistical Significance in R

This repository contains an R-based Jupyter Notebook that demonstrates how to visualize statistical significance using bar plots and box plots. The notebook utilizes the `ggplot2` and `ggsignif` libraries to highlight differences between groups in a dataset.

## Overview

Statistical significance testing is an important tool in data analysis. This notebook illustrates how to:

- Create bar plots and box plots using `ggplot2`
- Add significance annotations between groups using `ggsignif`
- Highlight comparisons between groups using custom annotations

The examples focus on placement data across different academic branches and a small group-based value dataset.

## Contents

- `Significance_Level.ipynb`: The main notebook file containing R code and plots demonstrating the use of `ggplot2` and `ggsignif` for visualizing group-wise comparisons.

## Requirements

To run this notebook, you need an R kernel in Jupyter and the following R packages:

- `ggplot2`
- `ggsignif`

You can install them within the notebook or in your R environment:

```r
install.packages("ggplot2")
install.packages("ggsignif")
