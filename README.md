Positional Age Effects on Expected Goals in Elite Football

This repository contains the R scripts and analytical workflow used in the study:

Positional age effects on expected goals in elite football: evidence from five European leagues**

Overview
The project investigates how player age and playing position relate to expected goals per 90 minutes (xG/90) and actual goals per 90 minutes among professional footballers across Europe’s top five leagues. Analyses are conducted using multilevel linear mixed-effects models with league-level random intercepts.

Contents
- `scripts/` – R scripts for data preprocessing, modelling, diagnostics, and visualisation  
- `figures/` – Code-generated figures used in the manuscript  
- `outputs/` – Model summaries and derived results (no raw data)

Data Availability
Raw player-level performance data are not included in this repository due to third-party licensing and confidentiality agreements with professional football leagues. The data were obtained from a proprietary performance provider and cannot be shared publicly.

Aggregated or derived data sufficient to reproduce the analyses may be made available from the corresponding author upon reasonable request, subject to approval from the data custodians and compliance with European data protection regulations.

Reproducibility
All analyses were conducted in R (v4.3) using packages including `lme4`, `lmerTest`, `tidyverse`, and `ggplot2`.  
The code is structured to allow replication using anonymized or simulated datasets where required by data-sharing restrictions.

Citation
If you use this code, please cite the associated manuscript.
