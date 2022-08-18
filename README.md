# Least Squares Method

## 1) Linear (ordinary) Least Squares (OLS) Regression 

The method of least squares is a standard approach in regression analysis to approximate the solution of a system (to model the system) by minimizing the sum of the squares of the residuals (a residual being the difference between an observed value and the fitted value provided by a model). The most important application is in data fitting [1].

If the data shows a linear relationship between two variables, the line that best fits this linear relationship is known as a least-squares regression line, which minimizes the vertical distance from the data points to the regression line. The term “least squares” is used because it is the smallest sum of squares of errors, which is also called the "variance" [2].

Note: Least squares regression is sensitive to outliers [3].


## 2) Generalized least squares (GLS) Regression

Generalized least squares is a technique for estimating the unknown parameters in a linear regression model when there is a certain degree of correlation between the residuals in a regression model. In these cases, ordinary least squares and weighted least squares can be statistically inefficient, or even give misleading inferences [4].

The generalized least squares (GLS) estimator of the coefficients of a linear regression is a generalization of the ordinary least squares (OLS) estimator. It is used to deal with situations in which the OLS estimator is not BLUE (best linear unbiased estimator) because one of the main assumptions of the Gauss-Markov theorem, namely that of homoskedasticity (the errors of the regression all have the same variance) and absence of serial correlation (their covariances are all equal to zero), is violated. In such situations, provided that the other assumptions of the Gauss-Markov theorem are satisfied, the GLS estimator is BLUE [5].

--------------------------------------------------------------------------------------------------------------

More information on:

https://towardsdatascience.com/ols-linear-regression-gauss-markov-blue-and-understanding-the-math-453d7cc630a5

https://towardsdatascience.com/generalized-least-squares-gls-mathematical-derivations-intuition-2b7466832c2c

--------------------------------------------------------------------------------------------------------------

#### References:

[1] https://en.wikipedia.org/wiki/Least_squares

[2] https://www.investopedia.com/terms/l/least-squares-method.asp#:~:text=Least%20Squares%20Regression%20Line,points%20to%20the%20regression%20line.

[3] https://www.mathsisfun.com/data/least-squares-regression.html

[4] https://en.wikipedia.org/wiki/Generalized_least_squares

[5] https://www.statlect.com/fundamentals-of-statistics/generalized-least-squares

Cods are adapted from:

https://www.statsmodels.org/dev/examples/notebooks/generated/ols.html

https://www.statsmodels.org/dev/examples/notebooks/generated/gls.html
