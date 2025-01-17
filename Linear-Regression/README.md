# K-Discovery-LR

- [Regression Analysis](#regression-analysis)
  - [Linear Regression](#linear-regression)
  - [Simple Regression](#simple-regression)
  - [Polynomial Regression](#polynomial-regression)
  - [Bias Variance Trade Off](#bias-variance-trade-off)
  - [General Linear Model](#general-linear-model)
- [Simple linear regression](#simple-linear-regression)
- [Multiple linear regression](#multiple-linear-regression)
- [Polynomial Linear Regression (Simple + Multiple)](#polynomial-linear-regression-simple--multiple)
- [Logistic regression](#logistic-regression)
- [Ordinal regression](#ordinal-regression)
- [Multinomial regression](#multinomial-regression)


## Simple linear regression
Involves one dependent variable (interval or ratio) and one independent variable (interval or ratio or dichotomous).<br>
When there is only one independent feature, it is known as Simple Linear Regression, and when there are more than one feature, it is known as Multiple Linear Regression.Similarly, when there is only one dependent variable, it is considered ```Univariate Linear Regression```, while when there are more than one dependent variables, it is known as ```Multivariate Regression```.<br>

The goal of the algorithm is to find the best Fit Line equation that can predict the values based on the independent variables.<br>
![image](https://github.com/user-attachments/assets/914e09bf-0174-451d-8ad9-46384413a9c9)

**What is the best Fit Line?**<br>
Our primary objective while using linear regression is to locate the best-fit line, which implies that the error between the predicted and actual values should be kept to a minimum. There will be the least error in the best-fit line.<br>

Here Y is called a dependent or target variable and X is called an independent variable also known as the predictor of Y. There are many types of functions or modules that can be used for regression. A linear function is the simplest type of function. Here, X may be a single feature or multiple features representing the problem.Linear regression performs the task to predict a dependent variable value (y) based on a given independent variable (x)). Hence, the name is Linear Regression. In the figure above, X (input) is the work experience and Y (output) is the salary of a person. The regression line is the best-fit line for our model. We utilize the cost function to compute the best values in order to get the best fit line since different values for weights or the coefficient of lines result in different regression lines.<br><br>

![image](https://github.com/user-attachments/assets/b848e502-3e4d-4961-9cd9-23e4aa977738)
<br><br>
```Cost function for Linear Regression```<br>
The cost function or the loss function is nothing but the error or difference between the predicted value ^𝑌 and the true value Y.

### Simple Linear Regression Mathematical Formulation
How to Find m, and b?<br>
There are two different two to find the values of m, and b <br>
```Every ML algorithm has a MOF (Mathematical Objective Function). The MOF of LR algorithm is to minimize the distances``` <br><br><br>

 There are two different two to find the values of m, and b<br><br>
1. **Closed Form Solution:** Direct Formula (Sklearn uses OLS technique), best for lower dimensional data. [Wikipedia](https://en.wikipedia.org/wiki/Closed-form_expression)
   
   Precalculus: In mathematics, an expression is in closed form if it is formed with constants, variables and a finite set of basic functions connected by arithmetic operations (+, 
   −, ×, /, and integer powers) and function composition. Commonly, the allowed functions are nth root, exponential function, logarithm, and trigonometric functions.[a] However, the set of basic functions depends on the context.<br><br>
   Usually you don't use the limit, differentiation, or integration.<br><br>
   Ex: Solving a quadratic expression using the quadratic formula.<br><br>
   [MOF in Linear Regression --> OLS](https://en.wikipedia.org/wiki/Ordinary_least_squares#:~:text=In%20all%20cases%20the%20formula,how%20we%20interpret%20this%20result).<br><br>
   
2. **Non-Closed From Scratch:** No Direct Formula | Usually found using differentiation or integration. <br>
   
   Gradient Descent an approximation technique is used to find m, and b.<br>
   
   Best for higher dimensional data | SGDRegression class in sklearn <br>

### Reression Metrics
1. MAE 
2. MSE
3. RMSE
4. R2 Score
5. Adjusted R2 Score

## Multiple linear regression
Features one dependent variable (interval or ratio) and two or more independent variables (interval or ratio or dichotomous).
[Theory + Code](2-MLR.ipynb)

## Polynomial Linear Regression (Simple + Multiple)
[Theory + Code ](3-PLR.ipynb)

## Bias Variance Trade-Off
[Theory](4-Bias-Variance-TradeOff.ipynb)

## Logistic regression
Deals with one dependent variable (dichotomous) and two or more independent variables (interval or ratio or dichotomous).

## Ordinal regression
Comprises one dependent variable (ordinal) and one or more independent variables (nominal or dichotomous).

## Multinomial regression
Includes one dependent variable (nominal) and one or more independent variables (interval or ratio or dichotomous).
