# ML-Assignment1 Linear Regression with Gradient Descent
This Python script demonstrates a simple linear regression model to predict profits for a food truck in various cities, based on the city's population. It uses gradient descent to minimize the cost function, optimizing the model parameters for the best fit against the training data.

# Features
1. Data Loading: The dataset is loaded into the variables x_train (independent variable: population of the city) and y_train (dependent variable: profit).
2. Data Visualization: A scatter plot is generated to visualize the relationship between the city's population and the food truck's profit.
3. Cost Function: Implements a function, compute_cost, to compute the cost for using a particular set of parameters, giving insight into how well these parameters predict the actual profits.
4. Gradient Descent: Utilizes compute_gradient to calculate the gradient of the cost function, and gradient_descent to iteratively adjust the model's parameters (w for weight and b for bias) to minimize the cost.
5. Prediction: After training, the model makes predictions on profits based on city populations.

# Usage
1. Load Dataset: The script starts by loading the training data (x_train and y_train).
2. Visualize Data: Next, it visualizes the dataset using a scatter plot.
3. Initialize Parameters: Initializes the model parameters w and b to zero.
4. Optimize Parameters: Runs gradient descent to optimize w and b.
5. Plot Regression Line: Plots the best fit line against the training data on a scatter plot.
6. Make Predictions: Uses the optimized parameters to predict profits for cities with populations of 35,000 and 70,000.

# Functions
load_data(): Loads the training dataset.\
compute_cost(x, y, w, b): Computes the cost function.\
compute_gradient(x, y, w, b): Computes the gradient of the cost function.\
gradient_descent(x, y, w_in, b_in, cost_function, gradient_function, alpha, num_iters): Performs gradient descent to minimize the cost function.\

# Requirements
This script requires NumPy for numerical operations and Matplotlib for plotting.

# Example Output
For population = 35,000, we predict a profit of $[predicted profit].\
For population = 70,000, we predict a profit of $[predicted profit].

# Notes
1. Ensure you have the required libraries installed before running the script.
2. Adjust alpha (learning rate) and iterations as needed to ensure convergence.
3. This example serves as an introductory demonstration of linear regression and gradient descent. For more complex datasets   or problems, consider using more sophisticated models or libraries.
