# Profit-Prediction-for-Food-Trucks
Implementation of Linear Regression with one Variable in MATLAB

PROBLEM DESCRIPTION:
Suppose you are the CEO of a restaurant franchise and are considering different cities for opening a new
outlet. The chain already has trucks in various cities and you have data for
profits and populations from the cities.
You would like to use this data to help you select which city to expand
to next.

DATASET:
The file ex1data1.txt contains the dataset for our linear regression problem. The first column is the "population of a city" and the second column is
the "profit of a food truck" in that city. A negative value for profit indicates a loss.

"plotData.m" file:-
Before starting on any task, it is often useful to understand the data by visualizing it. For this dataset, you can use a scatter plot to visualize the
data, since it has only two properties to plot (profit and population).

When we plot our data we get the following result:-


![image](https://user-images.githubusercontent.com/68648171/122887028-1b19e300-d35e-11eb-8634-1db4465564b3.png)



"gradientDescent.m" file:-
The main objective of Linear regression is to minimize the "cost function", which is given by 


![image](https://user-images.githubusercontent.com/68648171/122888092-26b9d980-d35f-11eb-8194-f5986679f698.png)


Our task is to find the suitable theta parameters in order to minimize the Cost Function. So we use Gradient descent algorithm to find the suitable theta parameters
of the hypothesis function. Gradient descent is algorithm is given by


![image](https://user-images.githubusercontent.com/68648171/122888965-fd4d7d80-d35f-11eb-94be-c730fa03af20.png)


After obtaining the theta parameter values we now implement the hypothesis function and further predict the output.
