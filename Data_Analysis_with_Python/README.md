IBM - Data Analysis with Python  
---------------------
A final project for Data Analysis with Python

Task description  
> In this assignment, you are a Data Analyst working at a Real Estate Investment Trust. The Trust would like to start investing in Residential real estate. You are tasked with determining the market price of a house given a set of features. You will analyze and predict housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on. A template notebook is provided in the lab; your job is to complete the ten questions. Some hints to the questions are given in the template notebook.  

Grading criteria  
> There are ten questions, each worth one point. For each item, you should have taken a screenshot of the output of each cell with the code that generated it, as directed in the final project Jupyter Notebook. You will not be graded on how well you wrote your code, just the output. However, you should provide the code used to obtain the answer in your screenshot. The provided code must run. Questions are independent. If you cannot answer a question or the answer you found is incorrect, you can still do the rest of the problems.

Question  
- Question 1:
  > Display the data types of each column using the attribute dtypes, then take a screenshot and submit it. Include your code in the image.
- Question 2:
  > Drop the columns "id" and "Unnamed: 0" from axis 1 using the method drop(), then use the method describe() to obtain a statistical summary of the data. Make sure the inplace parameter is set to True. Take a screenshot and submit it. 
- Question 3:
  > Use the method value_counts to count the number of houses with unique floor values, and use the method to_frame() to convert it to a data frame. Take a screenshot of your code and output and submit it.
- Question 4:
  > Use the function boxplot in the seaborn library to produce a plot that can help determine whether houses with a waterfront view or without a waterfront view have more price outliers. Take a screenshot of your code and boxplot and submit it.
- Question 5:
  > Use the function regplot in the seaborn library to determine if the feature sqft_above is negatively or positively correlated with price. Take a screenshot of the plot and the code used to generate it. Submit your screenshot.
- Question 6
  > Fit a linear regression model to predict the price using the feature 'sqft_living', then calculate the R^2. Take a screenshot of your code and the value of the R^2. Submit the screenshot.
- Question 7:
  > Fit a linear regression model to predict the 'price' using the list of features:
  > -  "floors"
  > -  "waterfront"
  > -  "lat"
  > -  "bedrooms"
  > -  "sqft_basement"
  > -  "view"
  > -  "bathrooms"
  > -  "sqft_living15"
  > -  "sqft_above"
  > -  "grade"
  > -  "sqft_living"
  >  Take a screenshot of your code and R^2 value and upload it.
- Question 8:
  > Create a pipeline object that scales the data, performs a polynomial transform, and fits a linear regression model. Fit the object using the features in the question above, then fit the model and calculate the R^2. Take a screenshot of your code and the R^2 and upload it.
- Question 9:
  > Create and fit a Ridge regression object using the training data, setting the regularization parameter to 0.1, and calculate the R^2 using the test data. Take a screenshot of your code and the R^2 and upload it.
- Question 10:
  > Perform a second-order polynomial transform on both the training data and testing data. Create and fit a Ridge regression object using the training data, setting the regularization parameter to 0.1. Calculate the R^2 utilizing the test data provided. Take a screenshot of your code and the R^2 and upload it.

