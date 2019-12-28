# Linear-Regression

Combined Cycle Power Plant Dataset:

The dataset contains data points collected from a Combined Cycle Power Plant over 6 years (2006-2011), when the power plant was set to work with full load. Features consist of hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V) to predict the net hourly electrical energy output (EP) of the plant.

# Main Tasks:

- Exploratory Data Analysis using scatter plots and statistical measures
- Fitting simple linear regression model for each of the predictors and finding if there is a statistically significant association         between the predictor and the response
- Fitting a multiple regression model to predict the response using all predictors and using null hypothesis to reject the insignificant     predictors
- Finding if there exists a nonlinear association between any of the predictors and the response
- Run a full linear regression model with all pairwise interaction terms to check association of interactions of predictors with the         response and whether any interaction terms are statistically significant
- Train a regression model on a randomly selected 70% subset of the data with all predictors involving all possible interaction terms and   quadratic nonlinearities and remove insignificant variables using p-values
- Perform KNN regression on the dataset and comparing the performance with linear regresssion model
