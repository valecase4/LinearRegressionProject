# Simple Linear Regression in Python

Link to the dataset: https://www.kaggle.com/datasets/himanshunakrani/student-study-hours

The dataset contains two columns:
- Number of hours student studied
- Marks the students got

It is possible to implement a linear regression model to find the line that best fits the data. Linear regression is a statistical model that estimates the linear relationship between a dependent variable and one or more independent variable. 

In this specific case, the dependent variable is _mark_ and the independent variable is _hours studied_.

Key points of the project:

- _train_test_split_ method by _sklearn.linear_model_ to split the dataset into random training set and test set. The training set is used to fit the model.
- Found the regression line equation. Particularly, found _w_ and _b_ parameters.
- Predicted values using the test set (_X_test_)
- Evaluated the model using _mean_squared_error_ from _sklearn.metrics_
- Calculated the value of cost function for _w_ and _b_. Cost is a measure of how well our model works.
