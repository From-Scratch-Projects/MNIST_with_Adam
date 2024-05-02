### Digit Recognizer From Scratch Using Adam

In this notebook, we will be implementing a Neural Network from scratch with Adam+Mini-Batch Gradient Descent. 

- Mini batch gradient descent is an optimization algorithm that updates model parameters based on the average of the gradients of a randomly selected small subset of training examples, rather than using the average of the gradients from all examples as in gradient descent or a single example.

- ADAM on the other hand, is an adaptive optimization algorithm we use for training machine-learning models. It uses the history of mini-batch gradients to find the direction of its update steps and tune its learning rates. It uses a combination of Momentum, and RMSprop, which leads to a robust, faster, less noisier model, than SGD+Momentum.
  
- The reason why we use mini-batch gradient descent instead of SGD is, mini-batch GD algorithm is more efficient and robust than the other variants of gradient descent (SGD, Vanilla GD). As the algorithm uses batching, all the training data need not be loaded in the memory, thus making the process more efficient to implement.

This is part 2 of the from-scratch series. If you are interested in part 1, you can find it <a href='https://github.com/Kiana-Jafari/Digit-Recognition-From-Scratch'>here!</a>
The Datasets are available to download in the file session. 
Also, please **note**, that we didn't use the same dataset for train-test, as we used in the previous lab. This is because, despite the better functionality of the Kaggle dataset and a higher size, the test data, which is separate data, does not include a ground truth (label) column, so we couldn't gain a deep intuition, of the model performance on the test set. Thus, we used the MNIST dataset from `Google Colaboratory`.

Hope the notebook would be useful!
