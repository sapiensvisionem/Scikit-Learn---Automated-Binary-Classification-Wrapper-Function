# Binary-Classification-Wrapper-Function-in-Python-Sklearn

Using Scikit-Learn library in Python, I created a wrapper function that automates binary classification with a single line of code. It takes in two arguments: data and location where it will store results in csv and rds format. The function runs 18 different statistical and machine learning algorithms from logistic regression to gradient boosting. The function returns the following four items in the given location:

1. summary table of evaluation metrics (accuracy, precision/recall, AUC, Kappa, etc) of every classification model on test set
2. save every model
