# footballscorespredictions
Football Score predictions
Did Polynomail regression to get the home team scores and away team scores. Also did Logistic Regression to find out whether a match was a loss, win or draw.

-- Project Status: [Active]
Project Intro/Objective
I created three models. 
The first one predicts the home team scores
The second predicts the away team scores
The third finds out whether a match was a lose, draw or win.

By Michael Gichuki
Methods Used
Data understanding to know the unique characteristics of the data set provided
Data cleaning to remove null values and columns that are not required for the analysis
Count of values
Bivariate analysis
Univariate analysis
Pandas Profiling Report
Technologies
Seaborn
Sklearn
Python
Pandas
Numpy
Project Description
The polynomial regression had a Root Mean Sqaured Error of 1.47 for the home team scores prediction. The away team had a model RMSE of 1.7. I perfromed cross validation and got on 700 models and got an RMSE of 0.8. 
The Logistic Regression model had an accuracy of 74%. I tuned the hyperparameters using the Random Search and got an improved accuracy of upto 99%.

Getting Started
Load on the data to python from the respective .csv files. Load Pandas and numpy

Project Owner: Brian Chege https://www.linkedin.com/in/brian-chege-8882a6b7/
