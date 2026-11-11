# Module 01 — Python, NumPy, Pandas & Git

## Overview

This module covers the foundational Python programming, numerical computing, data manipulation, and version control skills required for Machine Learning and Deep Learning.

## Learning Objectives

- Revise essential Python programming concepts.
- Work efficiently with NumPy arrays and numerical operations.
- Learn data manipulation and cleaning using Pandas.
- Practice Git and GitHub for version control.
- Develop practical skills through coding exercises and notebooks.

## Topics Covered

### 1. Python

**Notebook: [`python_codes.ipynb`](notebooks/python_codes.ipynb)**

**Topics Covered:**

- Python Syntax: Variables, data types, operators, conditional statements, loops, and user input.

- Data Structures: Lists and dictionaries for storing and managing data.

- Functions: Function definitions, parameters, return values, and method calls.

- OOP Basics: Classes, objects, constructors (**init**), instance attributes, and methods.

- Additional Concepts: Modules, importing libraries, random number generation, and basic CRUD operations.

**Note:** These programs were originally developed during earlier Python learning and reused as evidence of existing foundational knowledge.

### 2. NumPy

**Notebook: [`numpy_1.ipynb`](notebooks/numpy_1.ipynb) — NumPy Fundamentals**

- Array creation and initialization
- Array properties: shape, dimensions, size, dtype
- Data type conversion and reshaping
- Scalar and vector operations
- Mathematical, statistical, and trigonometric functions
- Matrix multiplication and dot product
- Indexing and slicing of multidimensional arrays
- Iteration, transpose, flattening, stacking, and splitting

**Notebook: [`numpy_2.ipynb`](notebooks/numpy_2.ipynb) — Intermediate NumPy**

- NumPy arrays vs. Python lists (speed and memory)
- Fancy indexing and Boolean indexing
- Broadcasting and broadcasting rules
- Mathematical implementations: Sigmoid and Mean Squared Error
- Handling missing values (`NaN`)
- Basic mathematical plotting using Matplotlib

**Notebook: [`numpy_3.ipynb`](notebooks/numpy_3.ipynb) — NumPy Utility Functions**

- Sorting, appending, and concatenation
- Unique values and dimension expansion
- Conditional operations using `np.where()`
- `argmax()` and `argmin()`
- Cumulative operations and percentiles
- Histograms and correlation coefficients
- Array filtering and manipulation
- NumPy set operations
- Clipping values

**Note:** These numpy topics are already covered, notebooks prepared during learning are attached here.

### 3. Pandas

**Notebook: [`pandas_1.ipynb`](notebooks/pandas_1.ipynb) — Pandas Fundamentals**

- Series creation with custom indexes
- DataFrame creation from dictionaries
- DataFrame attributes and inspection methods: shape, size, dtypes, head, tail, info, describe, sample
- Selecting single and multiple columns
- Label-based and position-based indexing with `loc` and `iloc`
- Boolean filtering and combining multiple conditions
- Filtering helpers: `isin()`, `between()`, `str.contains()`, and `query()`
- Sorting with `sort_values()`, `nlargest()`, `nsmallest()`, and `reset_index()`
- Loading and saving CSV and Excel files with `read_csv()`, `to_csv()`, `read_excel()`, and `to_excel()`

**Notebook: [`pandas_2.ipynb`](notebooks/pandas_2.ipynb) — Data Cleaning and Transformation**

- Detecting missing values with `isna()`, `notna()`, and missing-value percentages
- Handling missing data with `dropna()`, `fillna()`, `ffill()`, and `bfill()`
- Finding and removing duplicates with `duplicated()` and `drop_duplicates()`
- Data type conversion with `astype()`, `pd.to_numeric()`, and `pd.to_datetime()`
- Cleaning text data: stripping whitespace, fixing case, and checking values with `unique()` and `value_counts()`
- Renaming columns and dropping rows or columns
- Creating new columns with vectorized arithmetic, `assign()`, and `insert()`
- Conditional columns with `np.where()` and `np.select()`
- Binning numeric data with `pd.cut()`
- Transforming values with `map()`, `replace()`, and `apply()` (including row-wise `axis=1`)
- String operations with the `.str` accessor: splitting, replacing, and regex extraction

**Notebook: [`pandas_3.ipynb`](notebooks/pandas_3.ipynb) — Aggregation, Combining Data, and Time Series**

- Split-apply-combine with `groupby()` on single and multiple columns
- Aggregations: `mean()`, `sum()`, `min()`, `max()`, `count()`, and `size()`
- Multiple and named aggregations with `agg()`
- Group-level operations with `transform()` and `filter()`
- Frequency analysis with `value_counts()`, including proportions and percentages
- Cross-tabulation with `pd.crosstab()`
- Pivot tables with `pivot_table()` and reshaping with `unstack()`
- Combining tables with `merge()`: inner, left, right, and outer joins
- Merging on different key names, handling suffixes, and debugging with `indicator`
- Stacking and aligning data with `concat()` and `ignore_index`
- Converting and parsing dates with `pd.to_datetime()`
- Extracting date parts with the `.dt` accessor
- Filtering by date, using a date index
- Formatting dates with `strftime()`

### 4. Git & GitHub

- Repository creation and cloning
- Git commits and pushing changes
- Repository organization and documentation

## Environment and Dependencies

Learning notebooks are developed using Python and Jupyter Notebook in an Anaconda environment.

Dependencies are maintained in the repository's root `requirements.txt`.

## Completion Details

- **Start Date:** October 13, 2026
- **Completion Date:** October 21, 2026
- **Status:** Completed
