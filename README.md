# Linear-Regresion

In statistics, linear regression is a linear approach for modelling the relationship between a scalar response and one or more explanatory variables (also known as dependent and independent variables). The case of one explanatory variable is called simple linear regression; for more than one, the process is called multiple linear regression. This term is distinct from multivariate linear regression, where multiple correlated dependent variables are predicted, rather than a single scalar variable.
(From Wikipedia, the free encyclopedia: https://en.wikipedia.org/wiki/Linear_regression#:~:text=In%20statistics%2C%20linear%20regression%20is,as%20dependent%20and%20independent%20variables).

#### Continuous Value Data Generation
Generatation of 200 random values, distributed around 20. Plotting the histogram will generate a not linear distribution...
![image](https://user-images.githubusercontent.com/86708470/167184007-9f256135-7742-4df9-a8d6-3f7ba9f33a5a.png)


#### Simple Linear Regression
Simple linear regression is used to model the relationship between two continuous variables. Often, the objective is to predict the value of an output variable (or response) based on the value of an input (or predictor) variable.
(From BIO Statistics Collaboration of Australia: https://www.jmp.com/en_sg/statistics-knowledge-portal/what-is-regression.html).
![image](https://user-images.githubusercontent.com/86708470/167184707-8242ac9f-458b-43b8-8e5d-56915a997109.png)

#### KNN Regressor
KNN regression is a non-parametric method that, in an intuitive manner, approximates the association between independent variables and the continuous outcome by averaging the observations in the same neighbourhood. The size of the neighbourhood needs to be set by the analyst or can be chosen using cross-validation (we will see this later) to select the size that minimises the mean-squared error.
(From JMP Statistical Discovery LLC. All Rights Reserved: https://bookdown.org/tpinto_home/Regression-and-Classification/k-nearest-neighbours-regression.html).
![image](https://user-images.githubusercontent.com/86708470/167189337-b8da9515-830a-40db-b6f2-1c2127603823.png)


#### OLS Regressor with Stochastic Gradient Descent
Ordinary least squares (OLS) is a non-iterative method that fits a model such that the sum-of-squares of differences of observed and predicted values is minimized. Gradient descent finds the linear model parameters iteratively.
(From: https://www.saedsayad.com/gradient_descent.htm)

This algorithm is used as a prediction model in estimating costs for houses in Seattle, Washington.
![image](https://user-images.githubusercontent.com/86708470/167192558-74ea6996-6a3a-423b-8143-2f940c720a5f.png)
