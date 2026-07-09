# Reproducibility Guide

## Overview

This repository was developed to ensure that the analytical workflow supporting the study **Beyond Awareness: Understanding the Drivers of Sustainable Practice Adoption Among Built Environment Professionals** is transparent, reproducible, and easy to follow.

The original statistical analyses were conducted in **IBM SPSS Statistics**, while **Python** was subsequently used to independently reproduce the analyses, validate the statistical outputs, generate publication-quality figures, and provide a fully reproducible computational workflow.

The notebooks contained in this repository reproduce the descriptive statistics, correlation analyses, regression models, diagnostic tests, and visualizations presented in the accompanying manuscript.

---

# Repository Structure

```
Sustainable-Urban-Development-Nigeria/
│
├── data/
├── docs/
├── figures/
├── manuscript/
├── notebooks/
├── LICENSE
├── README.md
└── requirements.txt
```

---

# Software Requirements

The project was developed using:

| Software | Purpose |
|----------|---------|
| Python | Data analysis, visualization, reproducibility |
| Jupyter Notebook | Interactive computational workflow |
| IBM SPSS Statistics | Primary statistical analysis |

---

# Python Packages

Install all required packages using:

```bash
pip install -r requirements.txt
```

The repository currently requires:

- pandas
- numpy
- matplotlib
- scipy
- statsmodels
- openpyxl
- jupyter

---

# Dataset

The processed dataset is located in:

```
data/
```

The dataset has been cleaned before analysis.

Personally identifiable information has been removed.

---

# Running the Analysis

The analytical workflow should be executed in the following order.

## Notebook 1

```
01_Sustainable_Urban_Development_Analysis.ipynb
```

This notebook performs:

- Data loading
- Data cleaning
- Exploratory Data Analysis
- Descriptive statistics
- Correlation analysis
- Regression modelling
- Model diagnostics
- Interpretation of findings

---

## Notebook 2

```
02_Publication_Figures.ipynb
```

This notebook generates the publication-quality figures used throughout the accompanying manuscript.

Figures include:

- Figure 1 – Sample Characteristics
- Figure 2 – Sustainability Awareness
- Figure 3 – Sustainable Practice Adoption
- Figure 4 – Adoption–Contribution Gap
- Figure 5 – Correlation Matrix
- Figure 6 – Regression Coefficients
- Figure 7 – Conceptual Framework

---

# Validation Strategy

The analytical workflow follows a dual-platform validation approach.

1. Statistical analyses were first conducted using IBM SPSS Statistics.
2. Equivalent analyses were independently reproduced in Python.
3. Results from both platforms were compared to verify consistency.
4. Any discrepancies identified during reproduction were investigated against the original SPSS outputs before interpretation.

This approach strengthens confidence in the reported findings while improving transparency and reproducibility.

---

# Expected Outputs

Running both notebooks should reproduce:

- Descriptive statistics
- Summary tables
- Correlation matrices
- Multiple regression models
- Diagnostic statistics
- Publication-quality figures
- Conceptual framework

These outputs correspond directly to those reported in the accompanying manuscript.

---

# Notes

The Python notebooks were developed primarily to demonstrate a transparent and reproducible analytical workflow rather than to replace the original statistical analyses.

Readers interested in extending the analyses are encouraged to build upon the Python implementation contained in this repository.
