---
tags:
  - Exploratory Data Analysis
  - Machine Learning
---

# Predicting Life Expectancy Using Global Health Data
This project looks at how health, economic, and social factors are connected to life expectancy across countries using publicly available data from the World Health Organization. After cleaning the data and filling in missing values, the analysis explored patterns in variables like vaccination rates, infant mortality, healthcare spending, GDP, and poverty. Several models were then used to predict life expectancy, starting with linear regression and followed by more flexible machine learning approaches like Random Forest and XGBoost, with cross-validation used to compare performance.

The results showed that life expectancy can be predicted quite accurately using a mix of health and socioeconomic indicators, with Random Forest performing slightly better while still avoiding overfitting. Many of the findings matched common expectations, such as lower life expectancy being linked to higher poverty and infant mortality, and higher life expectancy being associated with strong vaccination coverage. Overall, the project highlights how data science techniques can be used to better understand global health patterns, while also acknowledging data limitations and the importance of careful, non-causal interpretation.

### Working Code
- Whitepaper here: [who_life.pdf](https://github.com/jewer/DataSciencePortfolio/blob/main/code/life/who_life.pdf)
- Notebook here: [who_life.ipynb](https://github.com/jewer/DataSciencePortfolio/blob/main/code/life/who_life.ipynb)