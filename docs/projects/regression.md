

---
tags:
  - Regression
  - Machine Learning
---

# Comparing Regression Algorithms

This notebook walks through a straightforward regression workflow using the classic auto MPG dataset, focusing on predicting fuel efficiency from vehicle characteristics. It starts by loading and cleaning the data, then explores relationships between variables using correlation analysis and visualizations. Several features like displacement, cylinders, horsepower, and weight are shown to be highly correlated with MPG, with a clear negative linear relationship between vehicle weight and fuel efficiency. These exploratory steps help motivate the modeling choices later on.

From there, the notebook builds and evaluates multiple regression models. A basic linear regression is trained using a train/test split, and performance is measured with R², RMSE, and MAE, showing that the model explains roughly 70% of the variance in MPG with reasonably low error. A decision tree regressor is then tested, which performs extremely well on the training data but poorly on the test set — a clear example of overfitting. To address this, the notebook finishes by experimenting with ridge regression and cross-validation, showing how regularization and better validation strategies can improve generalization. Overall, the notebook does a nice job demonstrating not just how to build regression models, but how to diagnose and respond to common modeling pitfalls.

### Working Code
- Notebook here: [regression.ipynb](https://github.com/jewer/DataSciencePortfolio/blob/main/code/regression/regression.ipynb)