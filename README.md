# LinearRegression
The code performs exploratory data analysis on the aircraft data and trains a linear regression model to predict the target variable.

Here is a summary of the code:

Read the data from a CSV file and create a pandas DataFrame named "aircraft".
Display the first 5 rows of the DataFrame using the head() method and get a summary of the DataFrame using the info() method.
Create a scatter plot of the "TAXI_OUT" column vs. the "DISTANCE" column to visualize the relationship between the two variables.
Calculate the pairwise correlation between columns of the aircraft DataFrame using a correlation matrix and create a heatmap of the correlation matrix.
Select specific columns from the DataFrame to create two new DataFrames, "x" and "y".
Split the data into training and testing sets using the train_test_split() function with a 70:30 ratio and a random seed of 32.
Standardize the input data using the StandardScaler method to normalize the data.
Train a linear regression model on the training data using the fit() method.
Use the trained model to make predictions on the test data using the predict() method.
Create a new DataFrame with the actual test values and the predicted values as two separate columns.
Evaluate the performance of the model using metrics such as mean squared error, mean absolute error, and R-squared.


