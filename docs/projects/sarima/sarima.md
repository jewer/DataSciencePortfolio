---
tags:
  - Machine Learning
  - Hyperparameter Tuning
---

# Time-series Retail Analysis

## Background
This notebook demonstrates a complete time series forecasting workflow using real-world U.S. retail sales data. Key techniques include reshaping wide-format data into a tidy time series structure, constructing a proper datetime index, and performing exploratory visualization to identify long-term trends and seasonal patterns. 

The analysis applies automated SARIMA modeling for seasonal forecasting, including train/test splitting, out-of-sample prediction, and quantitative evaluation using RMSE. To contextualize model performance, the notebook also implements a Holt–Winters exponential smoothing model as a comparative baseline. 

Together, these steps highlight practical skills in data preparation, seasonal time series modeling, model evaluation, and visual interpretation using Python’s pandas, statsmodels, and matplotlib libraries.

## Sample Visualizations
![SARIMA forecast](viz1.png)


![Compared to Holt-Winters](viz2.png)


## Working Code
To see a working example, [click here](https://github.com/jewer/DataSciencePortfolio/blob/main/code/sarima/sarima-notebook.ipynb).