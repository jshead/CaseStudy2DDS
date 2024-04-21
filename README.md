# CaseStudy2DDS

# Case Study 2 - Project Overview

**Author:** Jaren Shead  
**Date:** 2024-04-20  
**Output Format:** HTML Document  

## Introduction

This project analyzes a dataset with a focus on employee attrition, salary, and related factors. The analysis aims to identify key patterns and insights. This markdown file outlines the structure and content of the project.

## Repositories

This GitHub repository contains the following key components:

- **R Script (`Case Study 2_Final.R`)**: The main script for data analysis.
- **R Markdown (`Case Study 2 Knit.Rmd`)**: A combined report with code and narrative explanation.
- **Datasets**: CSV files containing data for analysis.
- **Output Files**: The results of the R Markdown knitting process.

## Project Contents

### Code Files
- **`Case Study 2_Final.R`**: Contains R code for data analysis, including data cleaning, processing, and visualization.
- **`Case Study 2 Knit.Rmd`**: A markdown file integrating R code with text for generating the HTML report.

### Datasets
- **`Case2PredictionsShead Attrition.csv`**: Contains data on employee attrition with the following columns:
  - `ID`, `Age`, `JobLevel`, `StockOptionLevel`, `TotalWorkingYears`, `OverTime`, `YearsInCurrentRole`, `YearsAtCompany`, `YearsWithCurrManager`, `JobSatisfaction`, and `Attrition`.
- **`Case2PredictionsShead Salary.csv`**: Data on employee salaries and related factors:
  - `ID`, `MonthlyIncome`, `TotalWorkingYears`, `MonthlyRate`, `NumCompaniesWorked`, `Attrition`, `Education`, `BusinessTravel`, `JobRole`.
- **`CaseStudy2-data.csv`**: Contains broader information about employees, including various demographic, work-related, and performance metrics. The dataset has 36 columns covering a wide range of variables.

## Presentation Materials
- **`Case Study 2 Knit.html`**: An html report generated from an analysis markdown file
- **Slide Decks**: Presentations summarizing the findings and insights from the data analysis.
- **Charts and Graphs**: Visual aids created from the analysis to support the presentation.
- **Shiny App**: https://jshead.shinyapps.io/CaseStudy2App/
## Usage and Notes

To run this project, follow these steps:

1. **Set Up R Environment**: Ensure R and RStudio are installed. Load necessary libraries.
2. **Execute the Code**: Open and run the R script and R Markdown file in your R environment.
3. **View the Output**: Check the HTML output generated by the R Markdown file.

### Required Libraries
Ensure you have installed the following libraries before running the code:

- `tidyverse`, `ggplot2`, `dplyr`, `tidyr`, `stringr`, `class`, `caret`, `e1071`, `mvtnorm`

## Usage
Refer to the README.md for instructions on how to use the materials in this repository.

## Notes
- Confidential data has been anonymized or removed as per Frito Lay's data policy.
- Analysis was conducted with R version 4.0.2.

## Contact
For questions or further information, please contact [Jaren Shead](jshead@smu.edu).
