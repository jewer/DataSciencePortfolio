---
tags:
  - Machine Learning
  - Exploratory Data Analysis
  - Regression
  - Clustering
---

# Retail Customer Segmentation

This project shows how data science can be used to make better business decisions. 

The main goals are to forecast sales demand and to group customers based on how they shop. The analysis uses a simulated retail dataset from Kaggle that includes basic transaction details like dates, product categories, quantities, and prices. The focus of the project is less about perfect predictions and more about demonstrating a practical workflow for exploring data, creating useful features, and applying machine learning in a retail context.

To do this, the project uses a mix of supervised and unsupervised learning techniques. Sales forecasting is handled as a regression problem, starting with Ridge regression as a stable baseline and then using a neural network to capture more complex patterns like seasonality and nonlinear relationships. Customer segmentation is done with K-means clustering using Recency, Frequency, and Monetary (RFM) features to identify different types of shoppers. 

Even though the data is simulated, the results show realistic trends and customer behaviors, making this a solid example of how predictive analytics can support inventory planning, marketing, and customer retention.

### Working Code
- Whitepaper here: [RetailCustomerAnalysis.pdf](https://github.com/jewer/DataSciencePortfolio/blob/main/code/retail/RetailCustomerAnalysis.pdf)
- Notebook here: [Retail notebook](https://github.com/jewer/DataSciencePortfolio/blob/main/code/retail/Appendix.ipynb)