# 3960-working-Crime-Analysis-Project
In this project, we will be using machine learning algorithms to analyze crime data and identify patterns and trends.Through this project,
we hope to contribute to the development of more effective and data-driven crime prevention strategies.
Dataset containing historical crime data for the neighborhood of interest in Edmonton was merged with demographics data of edmonton for year 2016
data was preprocessed by selecting relevant features and cleaning and transforming the data as necessary.
seven regression models were defined including linear regression, decision tree regression, random forest regression, gradient boosting regression,
XGBoost regression,SGD, Extra tree regressor.
Each model was trained on a subset of the data and evaluated its accuracy using metrics 
root mean squared error, and R-squared to predict the number of crimes in a particular neighborhood of Edmonton.accuracy of each model was evaluated and 
selected the top three performing models. 
Target was skewed,so both approaches were adopted with and without  transformed target regressor.
The XGBoosting regression, Gradient Boosting regression, and random forest regression models were the top three performing models.
Hyperparameter tuning was performed using five fold cross validation and feature selection was also tried.
Final model is able to predict number of crimes in certain neighborhoods with sociodemographics input features.
On testing data, it showed accuraccy of 69.8.
