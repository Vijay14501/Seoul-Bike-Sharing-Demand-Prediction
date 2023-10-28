# Bike-Sharing-Demand-Prediction
Porject summary

Data Preprocessing :

1.Getting the dataset

2.Importing libraries

3.Importing datasets

4.Finding Missing Data

5.Encoding Categorical Data

6.Data Cleaning and Feature Engineering

Exploratory data analysis(EDA) :

EDA is a fundamental part of data analysis that helps in ensuring data quality, understanding the data, and generating insights. It serves as the basis for making informed decisions throughout the data analysis process.
 Exploratory Data Analysis (EDA) on all the features in our dataset. Initially, we focused on our dependent variable, 'Rented Bike Count,' and applied data transformation techniques to prepare it for modeling. Subsequently, we conducted an in-depth examination of our categorical variables, removing those with overwhelmingly one-sided distributions to streamline our dataset. Simultaneously, we explored the numerical variables, assessing their correlations, distributions, and their relationships with the dependent variable. We also made the decision to eliminate certain numerical features that were predominantly populated with zero values, optimizing our data for modeling. Furthermore, we applied one-hot encoding to the categorical variables to make them suitable for machine learning algorithms.

For model selection and evaluation, we employed seven different machine learning algorithms:

1.Linear Regression

2.Lasso Regression

3.Ridge Regression

4.Elastic Net

5.Decision Tree

6.Random Forest

7.XGBoost
