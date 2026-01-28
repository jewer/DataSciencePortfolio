
---
tags:
  - PCA
  - Machine Learning
---

# Reducing Dimensionality with PCA

This notebook walks through a couple of common feature reduction and selection techniques using real datasets, with a focus on how they affect model performance. It uses the Ames housing dataset to explore dimensionality reduction in a regression context. After cleaning the data (handling missing values and one-hot encoding categorical features), a baseline linear regression model is trained to predict house prices. From there, the notebook applies PCA to retain 90% of the variance and compares the resulting model’s performance to the original. It also experiments with variance thresholding after scaling the features, showing how removing low-variance predictors impacts model accuracy and error.

### Working Code
- Notebook here: [pca.ipynb](https://github.com/jewer/DataSciencePortfolio/blob/main/code/pca/pca.ipynb)
