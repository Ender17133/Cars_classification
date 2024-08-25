[![Open in Jupyter](https://img.shields.io/badge/Open%20in-Jupyter-blue.svg?logo=jupyter)](https://github.com/Ender17133/Cars_classification/blob/main/classification.ipynb)

# Question 1: Classification using Logistic Regression

In this problem, you will develop a model to predict whether a given car gets high or low gas mileage based on the
Auto data set.

a) Create a binary variable, mpg01, that contains a 1 if mpg contains a value above its median, and a 0 if mpg
contains a value below its median.

b) Explore the data graphically in order to investigate the association between mpg01 and the other features.
Which of the other features seem most likely to be useful in predicting mpg01? Scatterplots and boxplots
may be useful tools to answer this question. Describe your findings.

c) Split the data into a training set and a test set using the seed 2401.

d) Perform logistic regression on the training data in order to predict mpg01 using the variables that seemed
most associated with mpg01 in (b). What is the test error of the model obtained?

# Question 2: Classification using Trees

Using the data set, and the same partition and target variable as in Question 1, do the following:

Fit a decision tree. Plot it and describe a few of the terminal nodes. What is the resulting training and test(validation)
misclassification rates? What is the optimal sized tree? Explain how you obtain the optimal size tree. 
