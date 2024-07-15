# K-Discovery-LR
## Regression Analysis
  1. Linear Regression
  2. Simple Regression
  3. Polynomial Regression
  4. General Linear Model  


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
  There are two different two to find the values of m, and b

    1. Closed Form Expression Direct Formula (Sklearn uses OLS technique), best for lower dimensional data. [Wikepedia](https://en.wikipedia.org/wiki/Closed-form_expression)
        Precalculus: In mathematics, an expression is in closed form if it is formed with constants, variables and a finite set of basic 		functions connected by arithmetic operations           (+, −, ×, /, and integer powers) and function composition. Commonly, the allowed 		functions are nth root, exponential function, logarithm, and trigonometric functions.[a]             However, the set of basic functions 		depends on the context.<br>
	    Usually you don't use the limit, differentiation, or integration.<br>
	    Ex: Solving a quadratic expression using the quadratic formula.<br>

	  [OLS](https://en.wikipedia.org/wiki/Ordinary_least_squares#:~:text=In%20all%20cases%20the%20formula,how%20we%20interpret%20this%20result).<br>

      
    2. Non-Close Form Expression: No Direct Formula | Usually found using differentiation or integration. <br>
        		Gradient Descent an approximation technique is used to find m, and b.<br>
		        Best for higher dimensional data | SGDRegression class in sklearn 


## Multiple linear regression
Features one dependent variable (interval or ratio) and two or more independent variables (interval or ratio or dichotomous).

## Logistic regression
Deals with one dependent variable (dichotomous) and two or more independent variables (interval or ratio or dichotomous).

## Ordinal regression
Comprises one dependent variable (ordinal) and one or more independent variables (nominal or dichotomous).

## Multinomial regression
Includes one dependent variable (nominal) and one or more independent variables (interval or ratio or dichotomous).
