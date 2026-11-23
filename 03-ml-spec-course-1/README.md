# Module 03 — Machine Learning Specialization: Course 1

## _Supervised Machine Learning: Regression and Classification_

## Overview

This module covers the first course of the Machine Learning Specialization: supervised learning with regression and classification. It builds the core ML concepts needed before moving on to deep learning.

## Learning Objectives

- Understand supervised learning and how a model learns from data.
- Implement linear regression and understand the cost function and gradient descent.
- Extend regression to multiple features.
- Understand and implement classification.
- Practice implementing models and evaluating results.

## Topics Covered

### 1. Regression and Gradient Descent [`↗`](01-regression-gradient-descent/)

**Notebook: [`1.1-regression-model.ipynb`](01-regression-gradient-descent/1.1-regression-model.ipynb) — Understanding and Implementing a Regression Model**

- Generating a synthetic regression dataset with `make_regression()`
- Visualizing inputs and targets with a scatter plot
- Training a linear regression model with scikit-learn (`LinearRegression`)
- Reading the learned weight (`coef_`) and bias (`intercept_`)
- Plotting the regression line over the data
- Predicting the output for a new input value

**Notebook: [`1.2-cost-function.ipynb`](01-regression-gradient-descent/1.2-cost-function.ipynb) — Cost Function**

- Implementing the squared error cost function `J(w, b)` from scratch with NumPy
- Comparing the cost for different values of `w` and `b`
- Plotting cost against the weight to see how the cost changes

**Notebook: [`1.3-gradient_descent.ipynb`](01-regression-gradient-descent/1.3-gradient_descent.ipynb) — Gradient Descent**

- Implementing the gradient calculation (`dj_dw`, `dj_db`) from scratch with NumPy
- Updating `w` and `b` in a loop using a learning rate
- Plotting the cost against iterations to check convergence
- Plotting the fitted line over the data

**Notebook: [`1.4-learning-rate-experiments.ipynb`](01-regression-gradient-descent/1.4-learning-rate-experiments.ipynb) — Learning Rate Experiments**

- Training the same model with different learning rates (0.001, 0.01, and 0.1)
- Comparing the final weight, bias, and cost for each learning rate
- Plotting the cost curves together to see how the learning rate affects convergence

### 2. Multiple Regression and Gradient Descent [`↗`](02-multiple-regression-gradient-descent/)

**Notebook: [`2.1-multiple-linear-regression.ipynb`](02-multiple-regression-gradient-descent/2.1-multiple-linear-regression.ipynb) — Multiple Linear Regression from Scratch**

- Working with multiple features: feature matrix `X`, number of examples `m`, and number of features `n`
- Prediction with and without vectorization using `np.dot()`
- Cost function for multiple features
- Vectorized gradient calculation and gradient descent
- Plotting cost against iterations to check convergence
- Comparing actual and predicted values, including a 3D scatter plot

**Notebook: [`2.2-feature-scaling.ipynb`](02-multiple-regression-gradient-descent/2.2-feature-scaling.ipynb) — Feature Scaling**

- Checking feature ranges with the minimum, maximum, mean, and standard deviation
- Implementing three scaling techniques from scratch with NumPy: mean normalization, Z-score normalization, and min-max scaling
- Comparing the scaled data and plotting each technique side by side

### 3. Classification [`↗`](03-classification/)

_Notebooks to be added._

## Environment and Dependencies

Notebooks are developed using Python and Jupyter Notebook in an Anaconda environment. Dependencies are maintained in the repository's root `requirements.txt`.

## Completion Details

- **Start Date:** November 21, 2026
- **Completion Date:** -
- **Status:** In Progress
