# Implementing neural network from scratch using numpy

To view editable version of the notebook click on 'Open in Colab' tab  
<a href="https://colab.research.google.com/drive/1f0RLDlFc72rLIxaBZHzPFN30HMw6s55d#scrollTo=8g5oZ0eJKT6O" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

# Problem statement

The problem statement is to implement the entire operational neural network using only numpy library and demonstrate the various steps associated with neural networks for the function y = x * x

# Notebook contents

- Introduction
- Steps involved in implementation of neural network
- Step 1: Get the data
- Step 2: Preprocess the data
- Step 3: Initialize the weights
- Step 4: Defining loss function
- Step 5: Implementing forward and backward propogation
- Step 6: Entire neural network operation
- Step 7: Visualizing the results

# Implementation overview

Steps involved to implement neural networks:

1. Get the input data (x) and output data (y)
2. Preprocess the data (scaling, standardization etc.)
3. Initialize the weights and biases for our hidden and output layers
4. Define the loss function
5. For each epoch out of 'n' epochs:
  - Perform forward propogation
  - Calculate the loss
  - Append this loss in a list to visualize the performance later
  - Perform weight updation mechanism
  - Calculate the derivative of loss w.r.t weights
  - Update the weights using gradient descent
6. Plot the results

# Tools and technologies used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://www.freecodecamp.org/news/content/images/size/w2000/2020/07/numpy.png" width=180 height=100>](https://numpy.org/) [<img target="_blank" src="https://miro.medium.com/max/1400/1*7oukapIBInsovpHkQB3QZg.jpeg" width=200>](https://colab.research.google.com/) 
