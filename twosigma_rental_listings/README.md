# TwoSigma/Renthop rental listing inquiries competition

https://www.kaggle.com/c/two-sigma-connect-rental-listing-inquiries  
The objective is to predict the level of interest that online rental-listings will receive, given a labeled dataset of ~50k listings.  
The listings need to be classified into "high", "medium" and "low" interest categories.  
There is an additional dataset of ~70k unlabeled listings, on which the predictions are to be submitted.

- data/: The training and test datasets in JSON format
- EDA.ipynb: Exploration and visualization of the data
- model_train.ipynb: Attempt at training a stacked classifier using Naive-Bayes and XGBoost
