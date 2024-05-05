### Digit Recognizer From Scratch Using Adam

In this notebook, we will implement a Neural Network from scratch using the Adam+Mini-Batch Gradient Descent algorithm. 

- Mini-batch gradient descent is an optimization algorithm that updates model parameters based on the average of the gradients of randomly selected small subsets of training examples. This is different from gradient descent or a single example, where the average of the gradients is used. 

- On the other hand, ADAM is an adaptive optimization algorithm used to train machine-learning models. It uses the history of mini-batch gradients to find the direction of its update steps and tunes its learning rates using a combination of Momentum and RMSprop. This leads to a robust, faster, and less noisy model than SGD+Momentum. 

- We use mini-batch gradient descent instead of SGD because it is more efficient and robust. As the algorithm uses batching, not all of the training data needs to be loaded into memory, making the process more efficient to implement. 

This is part 2 of the from-scratch series; If you are interested in part 1, you can find it <a href='https://github.com/Kiana-Jafari/Digit-Recognition-From-Scratch'>here!</a>
The datasets are available to download in the file session. Please **note** that we didn't use the same dataset for the train-test as we used in the previous lab. This is because, despite the better functionality of the Kaggle dataset and its larger size, the test data does not include a ground truth (label) column. Therefore, we couldn't gain a deep intuition of the model performance on the test set. Instead, we used the MNIST dataset from `Google Colaboratory`.

-----------------------------------------------------------------------------------------------------

The revised version of the notebook, which was uploaded immediately following the initial version, encompasses a range of additional techniques that complement the utilization of Adam Optimizer and Mini-Batch Gradient Descent techniques, with a view to enhancing the performance of our model. These techniques include: 

1. Evaluation of a Deep Neural Network (DNN) with an input layer, two hidden layers (instead of one), and an output layer. 
2. Implementation of L2 Regularization. 
3. Usage of two of the most commonly employed activation functions, namely **`Swish`** in conjunction with Leaky ReLU. 

The updated notebook provides a comprehensive understanding of the fundamental components required to construct an Artificial Neural Network from scratch.

Hope this notebook will be useful to everyone!
