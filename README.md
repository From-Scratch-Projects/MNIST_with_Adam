### Digit Recognizer From Scratch Using Adam
-----------------------------------------------------------------------------------------------------

In this notebook, we will implement a Neural Network from scratch using the Adam+Mini-Batch Gradient Descent algorithm. 

- Mini-batch gradient descent is an optimization algorithm that updates model parameters based on the average of the gradients of randomly selected small subsets of training examples. This differs from gradient descent or a single example, where the average of the gradients is used. 

- Conversely, ADAM is an adaptive optimization algorithm that trains machine-learning models. It uses the history of mini-batch gradients to find the direction of its update steps and tunes its learning rates using a combination of Momentum and RMSprop. This leads to a robust, faster, and less noisy model than SGD+Momentum. 

- We use mini-batch gradient descent instead of SGD because it is more efficient and robust. As the algorithm uses batching, not all training data needs to be loaded into memory, making the process more efficient to implement. 

The datasets are from `Google Colaboratory`, and available to download in the file session.

##### Also Note that:

This notebook encompasses a range of additional techniques that complement the utilization of Adam Optimizer and Mini-Batch Gradient Descent techniques, to enhance the performance of our model. These techniques include: 

1. Evaluation of a Deep Neural Network (DNN) with an input layer, two hidden layers (instead of one), and an output layer. 
2. Implementation of L2 Regularization. 
3. Usage of two of the most commonly employed activation functions, namely **`Swish`** in conjunction with **`Leaky ReLU`**. 

The updated notebook provides a comprehensive understanding of the fundamental components required to construct an Artificial Neural Network from scratch.

Hope this notebook will be useful to everyone!
