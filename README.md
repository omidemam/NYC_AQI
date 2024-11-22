# Air Quality Index (AQI) Analysis in New York State (2018-2022)

## Overview

This study analyzes the Air Quality Index (AQI) values in New York State (NYS) from 2018 to 2022 to determine whether there are statistically significant differences between the years. The analysis involves various transformations to stabilize variance and make the distribution more closely approximate a normal distribution. Statistical methods like ANOVA and Tukey's method were employed to detect differences between years. 

Key findings include:
- AQI values in 2018 are significantly different from 2020, 2021, and 2022.
- AQI values in 2019 are significantly different from 2020.
- Meteorological variables (temperature, precipitation, snow depth, wind speed) were used to explore correlations with AQI.
  - Positive correlation between temperature and AQI.
  - Negative correlation between wind speed and AQI.
  - The metorological data cant explaint the AQI variation there should be a confounding factor.

## Repository Contents

- **Data**: AQI data files (in CSV format or other relevant formats) for the years 2018-2022.
- **Code**: Python scripts used for data analysis, including:
  - Data cleaning and transformation (e.g., logarithmic and Box-Cox transformations).
  - Statistical tests (ANOVA, Tukey’s HSD test).
  - Correlation analysis.
- **Report**: A LaTeX document that explains the methodology, analysis, and results. You can access and compile the report using a LaTeX editor (e.g., Overleaf, TeXShop).
- **Figures**: Plots and graphs generated from the analysis to visually represent the results.

## How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/omidemam/NYC_AQI.git
