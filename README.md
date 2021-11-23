# Phishing-website-detection Project Overview
Classified phishing websites using one-hot encoded parameters and compared the predicted result from Logistic Regression, Random Forest, XGBoost models. Improved accuracy from 85% to 95% with hyperparameter tuning with grid and random search.

# Code and Resourcess used
Python version: 3.7
Packages: pandas, numpty, sklearn, matplotlib, seaborn, 
Other resources...

# Data 
Columns

# Data Cleaning 
After acquiring the data, I needed to clean it up so that it was usable for our model.
I made the following changes and created the following variables:




# EDA

# Model Building
First, I transformed the categorical variables into dummy variables. I also split the data into train and tests sets with a test size of 20%.

I tried three different models and evaluated them using Mean Absolute error. I choose MAE because

The three different models I tried:

# Model Performance
 
 The random forest model far outperformed the other approcahes on the test and validaiton sets.
 RF: MAE = 
 
 # Productionization
 
