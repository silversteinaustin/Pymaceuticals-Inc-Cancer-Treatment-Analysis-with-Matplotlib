# Pymaceuticals Inc: Cancer Treatment Analysis with Matplotlib

## Overview

Joining Pymaceuticals Inc., a pioneering pharmaceutical company focused on anti-cancer medication, I was tasked with analyzing data from a recent animal study on squamous cell carcinoma (SCC). This project aimed to evaluate the efficacy of Pymaceuticals' drug, Capomulin, against other treatment regimens. Utilizing Python's Matplotlib library, this analysis dives deep into the study's findings, generating crucial tables and figures for the clinical study's technical report and providing a top-level summary of the results.

### Objective

The primary objective was to leverage Matplotlib for data visualization to understand better and communicate the outcomes of the drug treatment study. Through meticulous data preparation, statistical analysis, and visualization, the project sought to draw meaningful conclusions about the drug regimens' effectiveness, particularly Capomulin's performance.

### Data Preparation

The analysis began by merging the `mouse_metadata` and `study_results` DataFrames, ensuring a comprehensive dataset for analysis. After identifying and removing any duplicate data entries, a clean dataset was established, forming the basis for all subsequent analyses.

### Summary Statistics

A comprehensive DataFrame was created to summarize key statistical measures across all drug regimens, including mean, median, variance, standard deviation, and SEM of tumor volumes.

### Visualizations

#### Bar and Pie Charts

- **Bar Charts:** Generated two identical bar charts using both Pandas and Matplotlib, illustrating the total number of measurements for each drug regimen.
- **Pie Charts:** Produced two identical pie charts with both Pandas and Matplotlib, depicting the distribution of female versus male mice in the study.

#### Quartiles, Outliers, and Box Plots

Calculated the final tumor volume for mice treated with Capomulin, Ramicane, Infubinol, and Ceftamin, identifying quartiles, IQR, and any potential outliers. A box plot visualized the distribution of final tumor volumes across these treatment regimens, highlighting outliers.

#### Line and Scatter Plots

- **Line Plot:** Selected a mouse treated with Capomulin to plot tumor volume versus time point.
- **Scatter Plot:** Illustrated the relationship between mouse weight and average tumor volume for the Capomulin regimen.

### Correlation and Regression

Calculated the correlation coefficient and linear regression model for mouse weight versus average tumor volume for the Capomulin treatment. The linear regression model was plotted over the scatter plot to visualize the relationship.

## Conclusions and Observations

The analysis yielded several key findings:

1. Capomulin and Ramicane were the most effective treatments in reducing tumor size.
2. There is a strong correlation between mouse weight and tumor volume, suggesting that weight may influence treatment efficacy.
3. The study had a balanced distribution of female and male mice, ensuring gender did not bias the results.

## Acknowledgments

I extend my gratitude to the Pymaceuticals executive team for entrusting me with this analysis. This project was an incredible opportunity to apply Matplotlib in a real-world context, enhancing my data visualization skills.

