# 📊 Statistical Analysis & Numerical Computing
Dimensionality reduction (PCA, LDA), Parameter Optimization (MLE, MAP), Singular Value Dicomposition (SVD) from scratch in Python

This repository contains a collection of high-performance implementations of core statistical and numerical methods. These projects demonstrate the intersection of mathematical theory and practical Python implementation, covering optimization, linear algebra, and machine learning foundations.

## 🚀 Projects Overview

### 1. Optimization: Gradient Descent (GD) & SGD
**File:** `GD_SGD.ipynb`
Implementation of iterative optimization techniques to find the minima of differentiable functions.
- **Key Features:** Custom implementation of Gradient Descent with **Backtracking Line Search** for optimal step-size selection.
- **Applications:** Testing convergence on complex loss landscapes and comparing performance against Stochastic Gradient Descent (SGD).

### 2. SVD-Based Image Classification
**File:** `SVD.ipynb`
A mathematical approach to computer vision using Singular Value Decomposition for MNIST digit classification.
- **Methodology:** Leverages the **Orthogonal Basis** of the column space (U matrix) to project unknown digits and classify them based on reconstruction error.
- **Highlights:** Binary classification (3 vs 4) achieving high accuracy through dimensionality reduction and subspace projection.

### 3. Parameter Estimation: MLE & MAP
**File:** `MLE_MAP.ipynb`
A deep dive into Frequentist vs. Bayesian parameter estimation.
- **Methodology:** Implements **Maximum Likelihood Estimation (MLE)** and **Maximum A Posteriori (MAP)** for polynomial regression.
- **Highlights:** Visualizing the impact of prior distributions on model weights and reducing overfitting through Bayesian regularization.

### 4. Stability in Linear Systems
**File:** `Linear_Systems.ipynb`
Analyzing the robustness of direct solvers for the system $Ax = b$.
- **Focus:** Numerical stability, **Condition Number ($K_2, K_{\infty}$)** analysis, and relative error propagation in ill-conditioned matrices.
- **Metrics:** Comparative analysis of NumPy's linear algebra solvers across varying matrix dimensions.

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** NumPy, SciPy (Linear Algebra), Matplotlib, Plotly (Interactive Visualizations)

---
*Developed by Kankana Ghosh as part of an Advanced AI & Statistical Modeling curriculum.*
