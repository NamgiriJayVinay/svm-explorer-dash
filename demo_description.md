### Info
**Polynomial Regression:** In this technique, a curve fits into the data points. In a polynomial regression equation, the power of the independent variable is greater than 1. Although higher degree polynomials give lower error, they might also result in over-fitting.

**Regularization:** is a technique used to solve the overfitting problem in statistical models. In machine learning, regularization penalizes the coefficients such that the model generalize better. We have different types of regression techniques which uses regularization such as Ridge regression and lasso regression.

**Ridge Regression:** Ridge regression performs **‘L2 regularization‘**, i.e. it adds a factor of sum of squares of coefficients in the optimization objective. Thus, ridge regression optimizes the 

**Lasso Regression:** 
Lasso, or Least Absolute Shrinkage and Selection Operator, is quite similar conceptually to ridge regression. It also adds a penalty for non-zero coefficients, but unlike ridge regression which penalizes sum of squared coefficients(the so-called L2 penalty), lasso penalizes the sum of their absolute values (L1 penalty). As a result, for high values of Lambda, many coefficients are exactly zeroed under lasso, which is never the case in ridge regression. 

**Logistic regression** is a supervised learning classification algorithm used to predict the probability of a target variable. The nature of target or dependent variable is dichotomous, which means there would be only two possible classes.In simple words, the dependent variable is binary in nature having data coded as either 1 (stands for success/yes) or 0 (stands for failure/no).
This regression uses Sigmoid Function to calculate the Probabilities

### Dataset uses for Visualising
for *Linear regression:* Random samples of data choosen through Numpy library 
for *Polynomial regression:* Random samples of data choosen through Numpy library 
for *Logistic regression:* DMV Dataset which has features of Test 1 and Test 2 and its results.It is a formulated data of People who appeared for Driving Test and their Results(DMV stands for Department of Motor Vehicles)
