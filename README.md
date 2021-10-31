# Sales-Analysis-and-Prediction-
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store. Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.
# Steps involved 
### Import Relevant Libraries
### Data Inspection
### Data Cleaning
### Exploratory Data Analysis
### Predcition using models

# SUMMARY : 
In this notebook, We will be using Linear Regression and Rnadom Forest Regressor and evaluate the best model by its R-Square value. 

## Linear Regression 
Linear regression attempts to model the relationship between two variables by fitting a linear equation to observed data. One variable is considered to be an independent variable, and the other is considered to be a dependent variable(Which is the variable to be predicted). For example, a modeler might want to relate the weights of individuals to their heights using a linear regression model.
A linear regression line has an equation of the form Y = a + bX, where X is the explanatory variable and Y is the dependent variable. The slope of the line is b, and a is the intercept (the value of y when x = 0).

![image](https://user-images.githubusercontent.com/79453056/139523935-25d9db93-b579-4365-9f39-9b3be5252aea.png)

By fitting a line through the sample training data points, we get a linear regression model and this line can be used to predict the output with different datapoints. 


## Random Forest 
Random Forest is a machine learning algorithm that can be used for a variety of tasks including regression and classification. It is an ensemble method, meaning that a random forest model is made up of a large number of small decision trees, called estimators, which each produce their own predictions. The random forest model combines the predictions of the estimators to produce a more accurate prediction.

Standard decision tree classifiers have the disadvantage that they are prone to overfitting to the training set. The random forest's ensemble design allows the random forest to compensate for this. Random forests are very good for classification problems but are slightly less good at regression problems. In contrast to linear regression, a random forest regressor is unable to make predictions outside the range of its training data.

To make a prediction for a new incoming example, we pass the relevant features of this example to each of the Ntree estimators. We will obtain Ntree predictions, which we need to combine to produce the overall prediction of the random forest. In the case of classification, we will use majority voting to decide on the predicted class, and in the case of regression, we will take the mean value of the predictions of all the estimators.

https://images.deepai.org/user-content/9196004107-thumb-1447.svg

