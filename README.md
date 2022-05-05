# XGBoost-Walkthrough
Walkthrough for Kaggle's Titanic dataset using XGBoost library.

This code was intended to be a guide to the overall process of building and evaluating a binary classification model using the XGBoost open source library.

Also view and run the code on Kaggle: https://www.kaggle.com/code/gustavoliberado/xgboost-walkthrough-titanic


This notebook uses data from datasets provided as part of the Kaggle competition Titanic - Machine Learning from Disaster. See original link: https://www.kaggle.com/competitions/titanic


# From the official data description:

# Variable Notes
pclass: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

sibsp: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.
