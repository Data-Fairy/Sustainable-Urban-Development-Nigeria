# Data Dictionary

## Overview

This document describes the variables contained in the processed dataset used throughout this project.

The dataset comprises survey responses from **147 built environment professionals in Nigeria** and was cleaned prior to statistical analysis. Variables include demographic characteristics, sustainability awareness measures, infrastructure indicators, organisational practices, and sustainable practice adoption metrics.

Unless otherwise stated, coded variables represent ordinal or categorical responses that were numerically encoded to facilitate statistical analysis.

---

# Dataset Information

| Attribute | Description |
|-----------|-------------|
| Study Design | Cross-sectional mixed-methods survey |
| Sample Size | 147 respondents |
| Geographic Scope | Nigeria |
| Population | Built environment professionals |
| Analytical Software | SPSS (primary analysis), Python (reproducibility and visualization) |

---

# Variable Dictionary

## Demographic Variables

| Variable | Type | Description |
|-----------|------|-------------|
| Age | Categorical | Respondent age group. |
| Gender | Categorical | Respondent gender. |
| Discipline | Categorical | Professional discipline within the built environment sector. |
| Region | Categorical | Nigerian geopolitical zone where the respondent primarily practices. |
| YearsExperience | Categorical | Years of professional experience. |
| YearsExperience_Code | Ordinal | Numerical coding of professional experience categories used in regression analyses. |

---

## Sustainability Awareness

| Variable | Type | Description |
|-----------|------|-------------|
| PolicyAwareness_NG | Categorical | Self-reported awareness of sustainability and climate-related policies in Nigeria. |
| PolicyAwareness_NG_Code | Ordinal | Numerical coding of sustainability policy awareness used in statistical analyses. |
| ClimatePolicy_Familiarity | Categorical | Familiarity with climate-related policies and initiatives. |
| ClimatePolicy_Familiarity_Code | Ordinal | Numerical coding of climate policy familiarity. |

---

## Sustainable Practice Adoption

| Variable | Type | Description |
|-----------|------|-------------|
| AdoptionScore | Continuous | Composite score representing respondents' overall adoption of sustainable professional practices. |
| PersonalAdoption | Categorical | Self-reported adoption of sustainable practices at the individual level. |
| PersonalAdoption_Code | Ordinal | Numerical coding of individual adoption. |
| OrgAdoption | Categorical | Reported organisational adoption of sustainable practices. |
| OrgAdoption_Code | Ordinal | Numerical coding of organisational adoption. |

---

## Infrastructure Variables

| Variable | Type | Description |
|-----------|------|-------------|
| InfraIndex | Continuous | Composite infrastructure availability index representing respondents' access to enabling infrastructure supporting sustainable practice implementation. |

---

## Sustainable Practice Domains

The following variables capture respondents' current implementation of sustainable practices across five domains.

| Variable | Description |
|-----------|-------------|
| WasteManagement | Current implementation of waste management practices. |
| EnergyEfficiency | Current implementation of energy-efficient practices. |
| GreenInfrastructure | Current implementation of green infrastructure practices. |
| ClimateResponsiveDesign | Current implementation of climate-responsive design practices. |
| WaterConservation | Current implementation of water conservation practices. |

---

## Perceived Areas of Greatest Contribution

These variables measure the sustainability domains in which respondents believe built environment professionals can make the greatest contribution.

| Variable | Description |
|-----------|-------------|
| Contribution_WasteManagement | Perceived contribution through waste management. |
| Contribution_EnergyEfficiency | Perceived contribution through energy efficiency. |
| Contribution_GreenInfrastructure | Perceived contribution through green infrastructure. |
| Contribution_ClimateResponsiveDesign | Perceived contribution through climate-responsive design. |
| Contribution_WaterConservation | Perceived contribution through water conservation. |

---

## Derived Variables

Several analytical variables were created during data preparation.

| Variable | Description |
|-----------|-------------|
| AdoptionContributionGap | Difference between current practice and perceived contribution across sustainability domains. |
| Infra_Policy | Interaction term between infrastructure availability and climate policy familiarity used in regression modelling. |

---

# Missing Data

The processed dataset was inspected for missing values prior to analysis.

Where necessary, variables were cleaned and recoded before inclusion in descriptive statistics, correlation analysis, and regression modelling.

---

# Notes

- Continuous variables were analysed using Pearson correlation and multiple linear regression where appropriate.
- Ordinal variables were numerically encoded solely for analytical purposes.
- Composite indices were developed from multiple survey responses to represent broader sustainability constructs.
- Personally identifiable information has been removed from the processed dataset included in this repository.

---

# Related Documents

For additional information, refer to:

- `Project_Summary.md`
- `Reproducibility_Guide.md`
- `01_Sustainable_Urban_Development_Analysis.ipynb`
- `02_Publication_Figures.ipynb`
