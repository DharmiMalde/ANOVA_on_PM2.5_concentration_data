# WindPM Analysis Project

## Overview

This project aims to investigate the impact of wind direction on PM2.5 concentrations at Sonia Vihar station in Delhi. The data was obtained from the CPCB website, specifically from the Sonia Vihar station, and analyzed to understand the relationship between wind direction and pollutant levels.

## Data Source

The data used for this analysis was sourced from the Central Pollution Control Board (CPCB) website. The dataset is in CSV format and originates from the Sonia Vihar station in Delhi.

## Data Processing

1. **Data Cleaning:** Missing values in the dataset were dropped to ensure a clean and complete dataset.
2. **Wind Direction Categorization:** Wind direction, originally in degrees, was converted into categorical data.
3. **Normality Check:** The Shapiro-Wilk Test was employed to assess the normality of the data. Subsequently, a log transformation was applied to achieve normality.

## Statistical Analysis

1. **Choice of Test:** Due to the non-normal distribution of the data, the Kruskal-Wallis test, a non-parametric alternative to ANOVA, was selected.
2. **Results:** The Kruskal-Wallis test revealed significant differences in PM2.5 concentrations among various wind direction pairs (p-value < 0.05).
3. **Post-hoc Analysis:** Pairwise Wilcoxon Test was conducted to identify specific wind direction pairs with significant differences.

## Key Findings

The wind direction pairs that showed significant differences (p-value < 0.05) are: E-NE, ESE-NE, NE-S, NE-SE, NE-SSE, NE-SSW, NE-SW, and NNE-SSW. Notably, the NE direction appeared most frequently in significant pairs, suggesting a significantly higher or lower mean compared to other directions. The mean PM2.5 concentration was observed to be highest for the NE direction, indicating a significant influence on pollutant transport from Uttar Pradesh to the 'Sonia Vihar' station in Delhi.







