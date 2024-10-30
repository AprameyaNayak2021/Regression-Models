## Regression-Models

# Motor Trend MPG Data Analysis

This project analyzes data from the `mtcars` dataset to determine the impact of transmission type on miles per gallon (MPG). Specifically, we aim to answer:
1. Whether an automatic or manual transmission results in better MPG.
2. The quantified MPG difference between automatic and manual transmissions.

## Project Overview

The `mtcars` dataset provides various features of a collection of cars, such as MPG, transmission type, weight, horsepower, and more. This analysis uses regression modeling and exploratory data visualization to evaluate how these factors relate to MPG and to quantify the effect of transmission type on fuel efficiency.

## Prerequisites

To successfully replicate this analysis, ensure you have:
- **R and RStudio**: The analysis uses the R programming language within an R Markdown (.Rmd) document.
- **Basic Statistical Knowledge**: Understanding of statistical tests (t-tests) and linear regression models is helpful.
- **Libraries Used**: This analysis requires the `ggplot2` library for data visualization, as well as base R functions for statistical testing and model fitting.

## Analysis Process

1. **Data Preparation**: 
   - Load the `mtcars` dataset (pre-installed in R).
   - Convert certain columns (e.g., `cyl`, `am`, `gear`) into factors to treat them as categorical data.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize MPG differences between automatic and manual transmissions using boxplots.
   - Run a t-test to determine if the observed MPG difference between transmission types is statistically significant.

3. **Regression Modeling**:
   - Fit a full regression model using `lm()` to identify the effect of all variables on MPG.
   - Use backward selection to refine the model to the most statistically significant factors.

4. **Model Interpretation**:
   - Interpret the final model to assess the relationship between MPG and key variables like weight, horsepower, and transmission type.
   - Generate diagnostics plots to validate model assumptions (e.g., normality, independence, constant variance).

5. **Report Generation**:
   - The final report is a concise PDF output of the R Markdown document, with the main text limited to approximately 2 pages. Supporting figures are included in an appendix, allowing up to 5 pages total.

## Report Summary

The report presents an executive summary, key findings, and model diagnostics. In summary:
- Manual transmissions are associated with a slight increase in MPG compared to automatic transmissions.
- However, variables like weight and horsepower are more significant predictors of MPG than transmission type alone.

## Results

A compiled PDF report presents the findings, with supporting figures in an appendix.

Thank you for exploring this analysis of vehicle fuel efficiency with us.


Keep Smiling, Keep Dancing!
