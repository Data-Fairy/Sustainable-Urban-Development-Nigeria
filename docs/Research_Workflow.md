# Overview

This document outlines the analytical workflow followed throughout the project, from research conception to reproducible analysis. The workflow combines conventional statistical analysis using IBM SPSS Statistics with a reproducible Python implementation that validates the reported findings and generates publication-quality visualizations.

The objective was not only to answer the research questions but also to create a transparent analytical pipeline that can be independently reviewed, reproduced, and extended.

# Project Workflow

Research Problem
        │
        ▼
Literature Review
        │
        ▼
Research Design
        │
        ▼
Questionnaire Development
        │
        ▼
Data Collection
(n = 147)
        │
        ▼
Data Cleaning & Coding
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Descriptive Statistics
        │
        ▼
Correlation Analysis
        │
        ▼
Regression Modelling
        │
        ▼
Model Diagnostics
        │
        ▼
Interpretation of Findings
        │
        ▼
Adoption–Contribution Gap Framework
        │
        ▼
Publication Figures
        │
        ▼
Manuscript Development
        │
        ▼
Python Reproducibility Workflow

# Phase 1: Research Design

The study began by identifying a gap in the literature concerning sustainable practice adoption among built environment professionals in Nigeria. While previous studies have frequently examined sustainability awareness and policy implementation, comparatively fewer have investigated the practical conditions that enable professionals to translate sustainability knowledge into practice.

A cross-sectional mixed-methods survey was therefore designed to collect quantitative and qualitative evidence from built environment professionals across Nigeria.

# Phase 2: Data Collection

Survey responses were obtained from 147 built environment professionals representing multiple disciplines, including architecture, urban planning, engineering, estate management, quantity surveying, environmental management, and construction.

The questionnaire collected information relating to:

Professional characteristics
Sustainability awareness
Climate policy familiarity
Infrastructure availability
Organisational sustainability practices
Individual sustainable practice adoption
Perceived areas of professional contribution

# Phase 3: Data Preparation

The raw survey data were reviewed before analysis.

Preparation included:

Variable coding
Data validation
Missing value assessment
Composite index construction
Preparation of analytical variables for statistical modelling

The resulting processed dataset formed the basis for all subsequent analyses.

# Phase 4: Statistical Analysis

The primary statistical analyses were conducted using IBM SPSS Statistics.

Analyses included:

Descriptive statistics
Pearson correlation analysis
Independent samples t-test
One-way ANOVA
Multiple linear regression
Model diagnostics

These analyses were used to evaluate the study hypotheses and identify the factors associated with sustainable practice adoption.

# Phase 5: Interpretation

Statistical findings were interpreted alongside qualitative responses obtained from the survey.

This combined interpretation enabled the study to move beyond identifying statistical relationships and towards explaining the practical barriers influencing implementation.

The analyses demonstrated that infrastructure availability consistently explained more variation in sustainable practice adoption than awareness-related variables.

# Phase 6: Conceptual Development

Drawing upon the statistical findings, the study developed the Adoption–Contribution Gap.

Rather than measuring only current implementation, this framework compares:

Current professional practice.
Perceived areas of greatest professional contribution.

The framework provides an evidence-based approach for identifying sustainability domains with the greatest unrealised implementation potential.

The findings indicate that built environment professionals generally recognise where they can contribute most. The principal challenge lies in creating the institutional, infrastructural, governance, and financial conditions necessary to enable implementation.

# Phase 7: Python Reproducibility Workflow

Following completion of the primary statistical analyses, the project was reproduced in Python.

The Python implementation served four purposes:

Independently reproduce the analytical workflow.
Validate statistical outputs against SPSS.
Generate publication-quality figures.
Develop a transparent and reproducible research repository.

This repository documents that computational workflow and provides a foundation for future extension of the analyses.

# Outputs

The project produced the following outputs:

Processed analytical dataset
Reproducible Python notebooks
Publication-quality figures
Conceptual framework
Research documentation
Journal manuscript
Workflow Summary

This project demonstrates a complete research pipeline spanning study design, statistical analysis, scientific interpretation, visualization, and reproducible documentation. By combining conventional statistical software with a transparent Python workflow, the repository enables independent verification of the analytical results while illustrating a practical approach to reproducible urban sustainability research.
