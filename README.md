# Project-Regularized-Regression
Repository project the data is about predicting housing price (medv) in Boston city. in this project I use ridge and lasso to see which model is the best by using Fit models on training data (lambdas = [0.01, 0.1, 1, 10]) the goal is to find the best lambda and see from RMSE, MAE, MAPE for evaluate the best models on the test data

## Data Set
1. Criminal rate (crim)
2. Residential land zoned proportion (zn)
3. Non-retail business acres proportion (indus)
4. Is bounds with river (chas)
5. Nitrogen oxides concentration (nox)
6. Number rooms average (rm)
7. Owner age proportion (age)
8. Weighted distance to cities (dis)
9. Accessibility index (rad)
10. Tax rate (tax)
11. Pupil-teacher ratio (ptratio)
12. Black proportion (black)
13. Percent lower status (lstat)

### Steps:
1. Split data: train - validate - test
2. Draw correlation plot on training data and perform feature selection on highly correlated features
3. Fit models on training data (lambdas = [0.01, 0.1, 1, 10])
4. Choose the best lambda from the validation set 
5. Evaluate the best models on the test data (RMSE, MAE, MAPE)
