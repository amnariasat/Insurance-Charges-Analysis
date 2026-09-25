# Insurance Charges Analysis — Python Project

## Project Overview
Analysed 1,338 customer records to identify key factors driving medical insurance charges. Cleaned and prepared the dataset, explored relationships between variables, and delivered actionable business recommendations.

Author: Amna Riasat
Data Analyst

## Dataset
- Source: Health Insurance Customer Data
- Total records: 1,338
- Features analysed: Age, Gender, BMI, Number of children, Smoking status, Region, Insurance charges

## Data Preparation
- Checked for missing values — none found
- Identified and removed one duplicate record
- Verified and corrected data types for all fields
- Created grouped categories:
  - BMI: Underweight, Normal, Overweight, Obese
  - Age: Young, Middle-aged, Senior

Resulted in a clean, consistent dataset ready for full analysis.

## Analysis and Visualisation
- Tools used: Python, Matplotlib
- Seaborn was not available in the Pyodide environment; all visualisations were built using Matplotlib
- Visual outputs included:
  - Line chart showing charges increasing steadily with age
  - Scatter plot demonstrating the relationship between BMI and higher costs
  - Correlation heatmap confirming age as the strongest positive factor, followed by BMI

## Key Findings
- Smoking status has the most significant impact — smokers show consistently much higher average and median charges
- Insurance costs rise steadily with age, especially for middle-aged and senior customers
- Higher BMI correlates strongly with increased charges, particularly in the overweight and obese ranges
- Region and gender show some variation but have relatively minor influence compared to health and age-related factors
- Charge distribution is right-skewed — most values are moderate, with a small number of very high-cost cases

## Business Recommendations
- Introduce premium discounts or incentives for customers who quit smoking
- Partner with healthcare providers to offer smoking cessation programmes
- Promote preventive care and regular health screenings for older customers
- Use BMI categories to support early risk identification and targeted support

## Summary
Smoking status, age, and BMI are the clearest drivers of insurance charges, directly linked to health risk and medical costs. These findings support fairer pricing models, better risk assessment, and more informed strategic decision-making.

