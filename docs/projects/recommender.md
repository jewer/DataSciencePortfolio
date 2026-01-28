---
tags:
  - Exploratory Data Analysis
  - Data Visualization
  - Presentation
---

# Using Collaborative Filtering to Build a Recommender

This notebook builds a simple movie recommender system step by step, starting with some light exploratory analysis to understand the ratings data. It begins with a baseline popularity-based recommender, which just suggests the most commonly or highly rated movies overall. This approach is straightforward and works as a reliable fallback, even though it doesn’t personalize recommendations. It’s used both as a benchmark and as a safety net later on if a user requests recommendations for a movie that isn’t found in the dataset.

From there, the notebook moves into collaborative filtering using cosine similarity on user rating vectors. Ratings are mean-centered to reduce user bias (since some people rate everything high and others rate everything low), and similarities are calculated based on shared rating patterns. The idea is to find users with similar tastes (“neighbors”) and recommend movies they liked that the target user hasn’t seen yet. The notebook also includes practical helper functions to make the system more usable, like a movie title lookup that tries exact matches, substrings, and fuzzy matching to handle typos or partial titles. Overall, the notebook focuses on building an intuitive, behavior-based recommender while balancing simplicity, robustness, and real-world usability.

### Working Code
- Notebook here: [recommender.ipynb](https://github.com/jewer/DataSciencePortfolio/blob/main/code/recommender/recommender.ipynb)