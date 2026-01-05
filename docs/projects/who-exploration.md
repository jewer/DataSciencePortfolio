---
tags:
  - Machine Learning
  - Exploratory Data Analysis
  - Regression
---

# Life Expectancy Predictions

This notebook explores global life expectancy data from the World Health Organization to better understand what factors are most strongly associated with lower life expectancy around the world. 

Using a Kaggle dataset with country-level health, economic, and demographic indicators, the analysis starts with exploratory data analysis to identify patterns, outliers, and correlations. Early visualizations show clear relationships between life expectancy, poverty, infant mortality, literacy, and healthcare access, with some of the lowest life expectancy outliers concentrated in parts of Africa. The goal at this stage is to build intuition about the data and identify which variables are most worth modeling.

The second half of the notebook focuses on preparing the data and building predictive models. Since the dataset includes multiple years per country, the data is cleaned, missing values are handled using forward and backward filling, and yearly data is aggregated into a single average profile per country. Several regression models are then trained to predict life expectancy, including linear regression, XGBoost, and random forest models. All three perform similarly well, suggesting the relationships in the data are relatively clean and not overly complex. 

Overall, the notebook demonstrates a full data science workflow, from data cleaning and feature selection to model evaluation, while highlighting how economic and health-related factors combine to influence life expectancy outcomes.

Notebook here:  https://github.com/jewer/DataSciencePortfolio/blob/main/code/who/WHOLifeExpectancy.ipynb