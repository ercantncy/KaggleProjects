Predicting the sale price of bulldozer using ML In this notebook , I am going to go through with the goal of predicting the sale price of Bulldozers.

# 1. Problem definition :
Predict the sale price of a particular piece of heavy equipment at auction based on it's usage, equipment type, and configuration.

# 2. Data
The data is downloaded from the Kaggle "Blue Book for bulldozer" competition. https://www.kaggle.com/c/bluebook-for-bulldozers/data

There are 3 main datasets:

Train.csv is the training set, which contains data through the end of 2011. Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public Leaderboard. Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

# 3. Evaluation
RMSLE (root mean squared log error) between the actual and predicted auction prices.
