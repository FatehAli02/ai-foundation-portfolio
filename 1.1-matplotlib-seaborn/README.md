# Module 1.1 — Matplotlib & Seaborn

## Overview

This module covers the basics of data visualization with Matplotlib and Seaborn, which are used for Exploratory Data Analysis (EDA) and for presenting Machine Learning results.

## Learning Objectives

- Choose the right plot for numerical and categorical data.
- Create and customize common plots with Matplotlib.
- Create statistical plots with Seaborn.
- Practice visualization on real datasets.

## Topics Covered

### 1. Matplotlib

**Notebook: [`matplotlib_1.ipynb`](notebooks/matplotlib_1.ipynb) — Matplotlib Fundamentals**

- Numerical vs. categorical data, and univariate vs. bivariate plots
- Line plots: multiple lines, titles, labels, colors, styles, markers, legends, axis limits, and grids
- Scatter plots, including point size from a data column
- Bar charts: horizontal, grouped, and stacked
- Histograms with custom bins and log scale
- Pie charts with `autopct` and `explode`
- Plot styles and saving figures with `savefig()`

**Notebook: [`matplotlib_2.ipynb`](notebooks/matplotlib_2.ipynb) — Advanced Matplotlib**

- Colored scatter plots with `cmap`, `alpha`, and `colorbar()`
- Figure size with `figsize`
- Annotations with `text()` and reference lines with `axhline()` and `axvline()`
- Subplots with `plt.subplots()`: multiple rows and columns, shared axes
- 3D scatter, line, and surface plots
- Contour plots with `contour()` and `contourf()`
- Heatmaps with `imshow()` on pivot tables
- Plotting directly from Pandas with `plot()`: scatter, bar, stacked bar, line, and pie

### 2. Seaborn

**Notebook: [`seaborn_1.ipynb`](notebooks/seaborn_1.ipynb) — Seaborn Fundamentals**

- Figure-level vs. axis-level functions
- Relational plots: `scatterplot()`, `lineplot()`, and `relplot()` with `hue`, `style`, and `size`
- Facet plots using `col`, `row`, and `col_wrap`
- Distribution plots: `histplot()`, `kdeplot()`, `rugplot()`, and `displot()`
- Bivariate histograms and KDE plots
- Matrix plots: `heatmap()` and `clustermap()`
- Datasets used: Seaborn `tips` and `titanic`, Plotly `gapminder` and `iris`

## Environment and Dependencies

Notebooks are developed using Python and Jupyter Notebook in an Anaconda environment. Dependencies are maintained in the repository's root `requirements.txt`.

## Completion Details

- **Start Date:** November 11, 2026
- **Completion Date:** -
- **Status:** In Progress
