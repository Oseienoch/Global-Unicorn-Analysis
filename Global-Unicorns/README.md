# Global-Unicons Analysis

## Overview
This repository hosts the "Global Unicorns Final Version" Jupyter Notebook, a detailed analysis of privately held 'Unicorn' companies worldwide, valued at 1 billion dollars or more. The project incorporates macroeconomic data and offers insights into the factors influencing unicorn valuations.

## Dataset Source
The original dataset was accessed from Kaggle, provided by the user Tahzeer: [Unicorn Startup Companies - July 2023](https://www.kaggle.com/datasets/tahzeer/unicorn-startup-companies-july-2023?resource=download).

## Interactive Dashboard
An accompanying interactive Tableau dashboard provides visualizations of the analysis: [Global Unicorn Overview on Tableau Public](https://public.tableau.com/app/profile/enoch.osei/viz/GlobalUnicornOverview/UnicornOverview).

## Contents
- `Global Unicorns Final Version.ipynb`: A Jupyter Notebook containing the comprehensive analysis of global unicorn companies. This notebook includes data cleaning, feature engineering, exploratory data analysis, and linear regression modeling.

## Analysis Highlights
- Identification of countries and cities with the highest count of Unicorns.
- Analysis of Unicorns achieving "Decacorn" and "Hectocorn" status.
- Yearly trends in companies achieving unicorn status from 2007 to mid-2023.
- Industry-wise distribution of Unicorns.
- Examination of top unicorn investors and their investment patterns.
- Linear regression analysis to understand factors influencing unicorn valuations.

## Methodology
- Data cleaning and type verification.
- Engineering additional variables for in-depth analysis.
- Incorporating World Bank macroeconomic data such as GDP, growth rates, interest rates, and corporate taxation.
- Descriptive statistics and exploratory data analysis for preliminary insights.
- Linear regression modeling for valuation analysis.

## Key Findings
- The age of a unicorn company significantly impacts its valuation.
- Macroeconomic factors and industry type show limited influence on valuation.
- Detailed findings on investor behaviors in the unicorn ecosystem.

## Requirements
- Python 3.x
- Libraries:
  - qgrid
  - pandas
  - numpy
  - statsmodels
  - seaborn
  - matplotlib
  - scikit-learn (specifically `LinearRegression`)

## Contributing
Contributions are welcome to extend the analysis or refine the methodologies. Feel free to fork this project, submit pull requests, or provide suggestions.

---

**NB**: 
- A **decacorn** is a private company, usually a startup, with a valuation greater than $10 billion.
- A **hectocorn** is a private company, usually a startup, with a valuation greater than $100 billion.

---
