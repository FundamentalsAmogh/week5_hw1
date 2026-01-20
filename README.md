# Exercise 1: Fragile States Index Analysis

**Live Report:** https://fundamentalsamogh.github.io/week5_hw1/

## Overview

This project analyzes the Fragile States Index (FSI) data from 2006-2023, published by the Fund for Peace. The analysis reads 18 Excel files from GitHub, combines them into a single dataset, and creates visualizations to explore trends in state fragility.

## Data Source

- **Source:** [Fragile States Index](https://fragilestatesindex.org/excel/)
- **Years:** 2006-2023 (18 files)
- **Countries:** 178 countries per year
- **Total Records:** 3,170 observations

## Columns Kept

| Column | Description |
|--------|-------------|
| Country | Country name |
| Year | Data year (2006-2023) |
| Rank | Fragility ranking (integer) |
| Total | Total FSI score |
| C1_Security_Apparatus | Cohesion indicator |
| C2_Factionalized_Elites | Cohesion indicator |
| C3_Group_Grievance | Cohesion indicator |
| E1_Economy | Economic indicator |
| E2_Economic_Inequality | Economic indicator |
| E3_Human_Flight_and_Brain_Drain | Economic indicator |
| P1_State_Legitimacy | Political indicator |
| P2_Public_Services | Political indicator |
| P3_Human_Rights | Political indicator |
| S1_Demographic_Pressures | Social indicator |
| S2_Refugees_and_IDPs | Social indicator |
| X1_External_Intervention | Cross-cutting indicator |

## Visualizations

1. **Boxplot:** Distribution of Total FSI scores by year (2006-2023)
2. **Faceted Histograms:** Comparison of cohesion indicators (C1, C2, C3) between 2013 and 2023

## Files

- `index.Rmd` - R Markdown source file
- `index.html` - Rendered HTML report
- `fsi-YYYY.xlsx` - Raw FSI data files (2006-2023)

## Author

Amogh Guthur
