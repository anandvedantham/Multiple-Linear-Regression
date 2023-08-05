# Multiple-Linear-Regression
Multiple Linear Regression is a statistical technique used to model the relationship between a dependent variable and two or more independent variables. It is an
extension of simple linear regression, which considers only one independent variable. In multiple linear regression, the goal is to find the best-fitting linear
equation that describes how the independent variables collectively influence the dependent variable.

## Implementation:

The main steps involved in performing a multiple linear regression analysis include:

- Data Collection: Gather data for the dependent variable and all relevant independent variables from a sample.

- Data Preprocessing: Clean the data, handle missing values, and check for outliers that could impact the analysis.

- Model Building: Fit the regression model by estimating the coefficients that minimize the sum of squared differences between the observed and predicted values.

- Model Evaluation: Assess the model's goodness of fit using metrics like R-squared, adjusted R-squared, and p-values for individual coefficients. These metrics 
  indicate how well the model explains the variance in the dependent variable.

- Assumption Check: Validate assumptions such as linearity, independence of errors, homoscedasticity (constant variance of errors), and normality of errors.

- Interpretation: Interpret the coefficients to understand the direction and magnitude of the relationship between each independent variable and the dependent 
  variable.

- Prediction: Once the model is validated, it can be used to make predictions on new, unseen data.

## Packages Used:

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Statsmodels
- Warnings
