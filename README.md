### Boston-House-Pricing Prediction
In this project Data Analysis has been performed on famous 'Boston-House-Pricing Dataset' which comes under umbrella term of Supervised Learning. 
The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. The following describes the dataset columns:

CRIM - per capita crime rate by town

ZN - proportion of residential land zoned for lots over 25,000 sq.ft.

INDUS - proportion of non-retail business acres per town.

CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)

NOX - nitric oxides concentration (parts per 10 million)

RM - average number of rooms per dwelling

AGE - proportion of owner-occupied units built prior to 1940

DIS - weighted distances to five Boston employment centres

RAD - index of accessibility to radial highways

TAX - full-value property-tax rate per $10,000

PTRATIO - pupil-teacher ratio by town

B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town

LSTAT - % lower status of the population

MEDV - Median value of owner-occupied homes in $1000's

The Data Analysis technically is a Multivariate Linear Regression Problem that consider only features independent of Multicollinearity, independent of errors, features with Homoscedascity and Multivariate Normality into a linear model. The Regression problem is simply solved with some assumptions based on human experience (not statistics) using Scikit-Learn library and predictions are generated using the object of `LinearRegression` class. The model is thus saved in pickled form at last for further work. This project is given shape of a Web Application by making an API. This API is well tested on `Postman API` testing software. The project is then dockered to run it on Cloud as well. I have dockered the project and also used `Github Actions` to run it on `Heroku Cloud`.

### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

Create a new environment



`conda create -p venv python==3.10 -y`


