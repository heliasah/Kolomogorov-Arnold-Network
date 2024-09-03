# Kolomogorov-Arnold-Network

# Overview 
This repository implements Kolmogorov-Arnold Networks (KANs), a novel neural network architecture inspired by the Kolmogorov-Arnold representation theorem.

# Reference 
This implementation is based on the approach detailed in the paper [**Kolmogorov-Arnold Neural Networks**](https://arxiv.org/abs/2404.19756), which introduces the KAN framework and explores its potential in function approximation and neural network design.


# Features

- Kolmogorov-Arnold Network (KAN) Architecture: The network structure is based on the Kolmogorov-Arnold representation theorem, enabling the decomposition of complex functions into simpler univariate functions.

- B-Spline Activation Functions: Custom B-Spline activation functions are used to allow for adaptive and smooth transformations of input data. These functions are parameterized by knots and coefficients, enabling the network to learn complex patterns more effectively.

- Iris Dataset Example: The network is demonstrated using the Iris dataset which is a well-known benchmark in machine learning, containing data on different species of flowers.

# Results
The training process outputs the loss at each epoch. The value of the loss decreases by each epoch which typically indicates that the model is learning and improving its predictions.
Additionally, a visualization of the B-spline activation function is provided to enhance clarity.
![Capture](https://github.com/user-attachments/assets/16d399d7-9616-41c5-8f0c-724b7805928d)


## Acknowledgements
This project was coded collaboratively by a group, other members are Maryam Jabbari and Shiva Saleh.
