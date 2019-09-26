# How to Win a Data Science Competition-Learn from Top Kagglers
Final Project assignment of the Predict Future Sales kaggle competition

In [this](https://www.kaggle.com/c/competitive-data-science-predict-future-sales) project we need to predict future sale of specific products of a software company given past sale recodrs.

This notebook includes:
- Exploratory data analysis (EDA)
  Some simple data exploration and graphs in order to better understand the problem
- Investigation for data leaks:
  Trying to understand if it is possible to harness data leakage.
- Feature Engineering:
  Adding categorical features, mean encoded features, lag features, mean encoded lag features etc.
- The Model:
  I used few different models: XGboost, Random Forest, Linear Regression, Neural Networks.
  I have used stacking to harness prediction from all these model: I used a linear regression to fit metafeatures originated from them.  
