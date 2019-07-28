# Linear-Regression-and-KNN-Regression

The task is to perform regression on Combined Cycle Power Plant dataset to predict the net hourly electrical
energy output (EP) of the plant.

## Dataset
The dataset contains data points collected from a Combined Cycle Power Plant over
6 years (2006-2011), when the power plant was set to work with full load. Features
consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP),
Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical
energy output (EP) of the plant.

## Exploratory Data Analysis
Scatterplots and various statistics like Mean, Median, Range, First Quartile, 
Third Quartile and Inter-Quartile Range of each of the variables in the dataset 
are used to analyze the data. 

## Linear Regression
For each predictor, fit a simple linear regression to predict the response variable EP 
and find out the statistically significant predictors using t-test. Also, fit a multiple 
regression model to predict the response using all the predictors and perform hypothesis 
testing. Compare the results of univariate regression models with multiple regression. <br/>
Fit a linear regression model by considering non-linear associations and pairwise interaction 
between the predictors and the response and do hypothesis testing.

## KNN Regression
Perform K-Nearest Neighbor Regression on the dataset using both normalized and raw features to 
predict the response. Plot the training and testing error for different values of K ranging from 1 to 100.
