# This is Ridge and Lasso Regression

Before Starting Ridge/Lasso Regression Lets Identify the Drawbacks of Linear Regression

- Linear Regression Is Limited to Linear Relationships
- Linear regression looks at a relationship between the mean of the dependent variable and the independent variables
- Linear Regression Is Sensitive to Outliers
- Data Must Be Independent 


 Ridge and Lasso regression are some of the simple techniques to reduce model complexity and prevent over-fitting which may result from simple linear regression.

- ## Ridge Regression
  
In ridge regression, the cost function is altered by adding a penalty equivalent to square of the magnitude of the coefficients.

![](../../../images/ridge_cost.png)

This is equivalent to saying minimizing the cost function 

![](../../../images/ridge_coeff.png)


So ridge regression puts constraint on the coefficients (w). The penalty term (lambda) regularizes the coefficients such that if the coefficients take large values the optimization function is penalized. So, ridge regression shrinks the coefficients and it helps to reduce the model complexity and multi-collinearity. 
