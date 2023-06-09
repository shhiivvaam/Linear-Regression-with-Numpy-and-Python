# Linear Regression With Numpy and Python

# Project Structure

This project on Linear Regression with NumPy and Python is divided into the following tasks:

## Task 1: Importing Libraries

## Task 2: Load the Data and Libraries

## Task 3: Visualize the Data

* Before starting on any task, it is often useful to understand the data by visualizing it.
* For this dataset, we can use a scatter plot using Seaborn to visualize the data, since it has only two variables: the profit and population.

## Task 4: Compute the Cost 𝐽(𝜃)

* We will look at the machinery that powers linear regression: Gradient Descent.
* We want to fit the linear regression parameters 𝜃 to our dataset using gradient descent.
* The objective of linear regression is to minimize the cost function J(𝜃).
* We will think of the cost as the error your model made in estimating a value.

## Task 5: Implement Gradient Descent in Python

* The parameters of our model are the 𝜃_j values.
* These are the values we will adjust to minimize the cost J(𝜃).
* One way to do this is to use the batch gradient descent algorithm.
* In batch gradient descent, each iteration performs the following update.
* With each step of gradient descent, the parameters 𝜃_j come closer to the optimal values that will achieve the lowest cost J(𝜃).
* 

## Task 6: Visualizing the Cost Function J(𝜃)

* To better understand the cost function J(𝜃), we will plot the cost over a 2-dimensional grid of 𝜃_0 and 𝜃_1 values.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/IynDYtiURWupw2LYlBVrfA_e45dd8bd7d5678f05b5798fa553d694f_Screenshot-from-2020-02-27-21-48-00.png?expiry=1686441600000&hmac=9QDBcJwPP66_cj1EYW8w7bmMhe2gG8TJOPHKtUlnqiY)

* The purpose of this graph is to show you how J(𝜃) varies with changes in 𝜃_0 and 𝜃_1.
* We can see that the cost function J(𝜃) is bowl-shaped and has a global minimum.

## Task 7: Plotting the Convergence

* Plot how the cost function varies with the number of iterations.
* When we ran gradient descent previously, it returns the history of J(𝜃) values in a vector “costs”.
* We will now plot the J values against the number of iterations.

## Task 8: Training Data with Univariate Linear Regression Fit

* Till now if we have correctly implemented and run gradient descent and arrived at the final parameters of our model, we can use these parameters to plot the linear fit.

## Task 9: Inference using the optimized 𝜃 values

* In this final task, we will use our final values for 𝜃 to make predictions on profits in cities of 35,000 and 70,000 people.
