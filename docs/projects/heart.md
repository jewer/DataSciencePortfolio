# Predicting Presence of Heart Disease

This project explores whether commonly collected clinical measurements can be used to predict the presence of heart disease using machine learning. Using a public UCI/Kaggle heart disease dataset with 1,025 patient records, the analysis focused on transforming routine diagnostic indicators—such as chest pain type, blood pressure, cholesterol, ECG results, exercise-induced angina, and imaging outcomes—into a predictive model that could support clinical decision-making. The goal was not to replace medical judgment, but to evaluate how data-driven tools might help identify higher-risk patients earlier and prioritize further testing. Particular attention was paid to data quality, feature encoding, correlation analysis, and ethical considerations around false negatives in a healthcare context.

From a modeling perspective, Logistic Regression was used as an interpretable baseline, while Gradient Boosting was applied to capture non-linear relationships common in clinical data. Model performance was evaluated using k-fold cross-validation, accuracy, recall, and ROC-AUC, with recall emphasized due to the cost of missed diagnoses. The Logistic Regression model achieved strong baseline performance, while the Gradient Boosting model substantially improved predictive accuracy (ROC-AUC ≈ 0.98), highlighting the value of ensemble methods for structured medical datasets. Key predictors identified across models aligned with established clinical knowledge, reinforcing the validity of the results. 

Overall, the project demonstrates a complete applied data science workflow—from exploratory analysis and feature selection to model comparison and ethical assessment—illustrating how predictive analytics can responsibly support healthcare decision-making.

### Working Code
- Whitepaper here: [ChildcareCosts.pdf](https://github.com/jewer/DataSciencePortfolio/blob/main/code/heart/HeartDisease.pdf)
- Powerpoint here: [ChildcareCosts.pptx](https://github.com/jewer/DataSciencePortfolio/blob/main/code/heart/HeartDisease.pptx)
- Notebook here: [ChildcareCosts.ipynb](https://github.com/jewer/DataSciencePortfolio/blob/main/code/heart/HeartDisease.ipynb)