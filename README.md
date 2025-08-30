# Regression Analysis of Diamond Prices

## An exploratory analysis of diamond prices using linear regression

This report sought to fit a linear regression model in R for diamond price, choosing the most relevant predictors out of 4 chosen to do this, carat, color, clarity, and depth. The final model was chosen after:
* Diagnostic checking of the model's assumptions 
* Transforming predictors and the response
* Checking model fit with adjusted $R^{2}$ values
* Employing criterion based variable selection methods like stepwise AIC (Akaike Information Criterion)
* Analyzing multicollinearity with VIF (Variance Inflation Factor)
* Examining leverage and influential points using Cook's distance 

Additionally, EDA was run, and R outputs were thoroughly interpretted like the linear regression `summary()` function output for instance. The data was taken from the [Diamonds Prices](https://www.kaggle.com/datasets/nancyalaswad90/diamonds-prices) dataset on Kaggle, randomly sampling 1000 observations. 


