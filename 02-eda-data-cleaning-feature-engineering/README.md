# Module 02 — EDA, Data Cleaning & Feature Engineering

## Overview

This module covers how to explore, clean, and prepare data for Machine Learning, from Exploratory Data Analysis (EDA) to Feature Engineering.

## Learning Objectives

- Perform univariate and bivariate analysis to understand a dataset.
- Assess data quality and clean messy data.
- Create and transform features to improve model inputs.
- Apply these steps together on real datasets.

## Topics Covered

### 1. Exploratory Data Analysis (EDA)

**Notebook: [`eda.ipynb`](eda/eda.ipynb) — Exploratory Data Analysis**

- Why EDA is done, and why it is iterative
- Column types: numerical, categorical, and mixed
- Univariate analysis of numerical columns (`describe()`, histogram, KDE, skewness, box plot, outliers, missing values)
- Univariate analysis of categorical columns (`value_counts()`, bar and pie charts)
- Bivariate analysis: choosing plots for numerical vs. categorical column combinations
- Contingency tables with `pd.crosstab()` and heatmaps
- Comparing distributions across groups using KDE plots
- Feature engineering from EDA findings: individual fare, family size, family type, surname, title, and deck
- Dataset used: Titanic (`train.csv` and `test.csv`)

### 2. Data Cleaning

**Notebook: [`data-cleaning.ipynb`](data-cleaning/data-cleaning.ipynb) — Assessing and Cleaning Data**

- Dirty data vs. messy (untidy) data
- Manual and programmatic assessment (discover, then document)
- Assessment with `info()`, `describe()`, `duplicated()`, and `sample()`
- Data quality dimensions: completeness, validity, accuracy, and consistency
- Cleaning workflow: define, code, test, working on copies of the data
- Handling missing values with `fillna()`
- Separating phone and email using regex
- Combining tables with `concat()` and `merge()`
- Reshaping with `melt()` and splitting columns with `.str.split()`
- Dataset used: clinical trials data (patients, treatments, and adverse reactions)

### 3. Feature Engineering

_Notebooks to be added in [`feature-engineering/`](feature-engineering/)._

## Environment and Dependencies

Notebooks are developed using Python and Jupyter Notebook in an Anaconda environment. Dependencies are maintained in the repository's root `requirements.txt`.

## Completion Details

- **Start Date:** November 17, 2026
- **Completion Date:** -
- **Status:** In Progress
