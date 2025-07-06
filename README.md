# Statistical Analysis of Salary Disparities Among Early-Career Developers: US vs. Germany

**Author:** Khalil Hammod  
**Date:** July 2025

## Project Summary

This project presents a robust, data-driven analysis of salary differences between early-career software developers (ages 18–24) in the United States and Germany, utilizing the 2024 Stack Overflow Developer Survey. The analysis leverages rigorous data cleaning, statistical hypothesis testing, and multivariate regression modeling to quantify and interpret cross-country compensation disparities.

## Analytical Objectives

- Identify and measure the average salary gap between early-career developers in the US and Germany.
- Employ inferential statistical methods to assess significance.
- Control for key confounders, including education level and professional experience, via regression analysis.

## Methodology

- **Data Source:** Stack Overflow 2024 Developer Survey (public)
- **Preprocessing:** Filtering, missing value handling, country-specific salary thresholds, and outlier removal
- **EDA:** Visualization of distributions, assessment of skewness and outliers
- **Transformation:** Logarithmic salary transformation and extreme quantile trimming
- **Hypothesis Testing:** Welch’s t-test to compare means
- **Modeling:** OLS regression with categorical and continuous covariates
- **Diagnostics:** Residual analysis to validate model assumptions

## Key Results

- US early-career developers earn **approximately 73% more** than those in Germany, with the difference remaining robust after adjusting for education and experience.
- The salary gap is statistically significant (p < 0.05), as demonstrated by both hypothesis testing and regression analysis.
- Model diagnostics confirm the validity of statistical inferences.

## Technical Skills Demonstrated

- Advanced data preprocessing and wrangling (Pandas)
- Exploratory data visualization (Matplotlib, Seaborn)
- Inferential statistics (t-tests, confidence intervals)
- Regression modeling and interpretation (Statsmodels)
- Statistical diagnostics and model validation

## Usage

- The Jupyter notebook (`salary_analysis_us_germany.ipynb`) contains all code and commentary for replication.
- To run the analysis, ensure Python 3.x and the following libraries are installed:
    - pandas
    - numpy
    - matplotlib
    - seaborn
    - scipy
    - statsmodels

## License

This project is for educational and demonstration purposes, leveraging public survey data.  

