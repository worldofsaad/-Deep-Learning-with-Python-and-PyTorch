# Deep Learning with Python and PyTorch
I used Python and its popular libraries such as NumPy and Pandas, as well as the PyTorch Deep Learning library. I then applied them to build Neural Networks and Deep Learning models.

## 1. Tensors and Gradients
- **Tensors**: Tensors are an essential part of PyTorch; there are complex mathematical objects in and of themselves. Fortunately, most of the intricacies are not necessary. In this section, I compared them to vectors and numpy arrays.

- **Derivatives**: In this section, took a look at simple derivatives and partial derivatives. And went over a cool hack that allows you to calculate the derivative of a function for multiple values using PyTorch Library.

- **Dataset**: In this section, I constructed a basic dataset by using PyTorch and learnt how to apply basic transformations to it. Also, used a prebuilt dataset and then used some prebuilt dataset transforms.

## 2. Fundamentals of Linear Regression
- **1D Training One Parameter**: In this section, I trained a model with PyTorch by using data that I created. The model only has one parameter: the slope

- **1D Training Two Parameter**: In this section, I trained a model with PyTorch by using the data that I created. The model will have the slope and bias. And l reviewed how to make a prediction in several different ways by using PyTorch

- **Stochastic Gradient Descent**: In this section, I practiced training a model by using Stochastic Gradient descent and compared it with Batch Gradient Descent we used in earlier section.

- **Mini-Batch Gradient Descent**: In this section, l practiced training a model by using Mini-Batch Gradient Descent.

- **PyTorch Way**: I created a model the PyTorch way in this section, this helps as models get more complicated.

- **Training and Validation Data**: In this section, I learnt to select the best learning rate by using validation data.

- **Early Stopping**: In this section, I performed early stopping and save the model that minimizes the total loss on the validation data for every iteration. (*Note*: Early Stopping is a general term. We will focus on the variant where we use the validation data. You can also use a pre-determined number iterations.)

- **Multi Linear Regression**: I performed Linear Regression involving multiple parameters as well as output using nn,Modules.

## 3. Logistic and Softmax Regression
- **Logistic Regression Prediction**: In this section, we will cover logistic regression using PyTorch.

- **Logistic Regression Training**: I see what happens when we use the root mean square error cost or total loss function using random initialization for a parameter values and also by selecting a bad initialization value for the parameter values and then try to solve issue with cross entropy.

- **Softmax Regression**: In this section, I used Softmax to classify three linearly separable classes, the features are in one dimension and then I used a single layer Softmax to classify handwritten digits from the MNIST database.

## 4. Feed Forward Neural Network
- **Neural Network**: In this section, I used a single-layer neural network to classify non linearly seprable data in 1-D database. Alsp, I explored how many neurons it takes to classify a noisy XOR data with one hidden layer neural network. Then I used a single layer neural network to classify handwritten digits from the MNIST database.

- **Activation Functions**: I compared different Activation Functions i.e. Sigmoid, Relu & Tanh by using them on MNIST
