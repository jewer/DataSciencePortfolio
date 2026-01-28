---
tags:
  - Hyperparameter Tuning
---

# GridSearch for hyperparameter tuning

This notebook walks through building and tuning a few different machine learning models to predict loan outcomes. After loading and cleaning the loan training data (including dropping IDs and preparing features), the notebook tests several common classification approaches: K-Nearest Neighbors, Logistic Regression, and Random Forest. Instead of guessing hyperparameters, it uses GridSearchCV to systematically try different settings for each model and compare their performance using cross-validation.

In the end, Logistic Regression comes out on top. The grid search identifies an optimal regularization strength (C) that balances model complexity without overfitting, and the liblinear solver is used since it’s well-suited for binary classification problems like this one. Overall, the notebook demonstrates a practical, methodical approach to model selection—trying multiple algorithms, tuning them properly, and letting the data (not intuition alone) decide which model performs best.


### Working Code
- Notebook here: [gridsearch.ipynb](https://github.com/jewer/DataSciencePortfolio/blob/main/code/gridsearch/gridsearch.ipynb)
