# MovieRevenuePredictor
Movie Revenue Predictor - Linear Regression 

## File Name 
https://github.com/Mr-CBrown/MovieRevenuePredictor/blob/main/regression.ipynb

## Technologies Used:
Jupyter Notebook, Python (Pandas, Matplotlib, Scikit)

### Description:
Use data to predict the potential movie revenue based upon how much is spent on the production budget. In order to complete this task I will be using an online data set found on at Kaggle.com (file is posted in the repository). The main objective will be to utlize two columns, revenue and budget, as my varaiables in my simple linear regression analysis. 

The order this will be complete will follow:
1) Importing required python packages 
2) Use Pandas to read the csv file downloaded from Kaggle
3) Create a data frame to manipulate and clean data
4) Remove excess columns 
5) Identify potential filters and use them 
6) Remove potential outliers within budget and revenue columns
7) Remove null values 
8) Plot values on X/Y Plane using Matplotlib
9) Use Scikit to train the regression model
10) Determine the Coefficent and Intercept of the regression line
11) Plot the Regression Line
12) Predict the output (Revenue) based upon and input (Budget)
13) Find the R-value to determine strength of the correlation bewteen the two variables 

### Findings 
For such a simplified linear regression model, the R value, .53, was better than I expected. As you can see from the results, with a 5 million dollar this model predicts roughly 11 million dollar revenue. Now I just need to find 5 million dollars to make a movie.....

