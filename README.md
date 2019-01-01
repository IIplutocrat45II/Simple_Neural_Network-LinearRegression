# Simple_Neural_Network-LinearRegression  [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Get%20over%20170%20free%20design%20blocks%20based%20on%20Bootstrap%204&url=https://www.froala.com/design-blocks&via=froala&hashtags=bootstrap,design,templates,blocks,developers)
<b>Objective: </b>For basic understanding on how a neural network works 

### Getting Started

Neural network is an interesting and a fascinating topic in today's world but yet it is harder to visualize it in code format, so to get a good grasp over the fundamentals of neural network in coding this repository provides a basic python notebook where neural network is implemented in a simple linear regression and each step is clearly explained for better understanding.

### Prerequisites

What things you need to install the software and how to install them

```
Pandas
Numpy
Matplotlib
tqdm
tensorflow
```

### Installing

A step by step series of examples that tell you how to get a development env running

If the required dependencies (prerequisites) are already installed, please skip this part.
To install these prerequisites, Open the respective command line interface (powershell, terminal) and paste the following:

```
pip install pandas
pip install numpy
pip install tensorflow
pip install tqdm
pip install matplotlib

```
### What it does ??
This Neural network finds an optimal line which minimizes the loss function for the given dayaset and we use mean squared error(MSE) as the cost function.

## How it works ??
![](https://www.cc.gatech.edu/~san37/img/dl/perceptron.jpg)

This neural network has an input layer which is matrix of input features and an output layer of a target vector. To make things simple we predefine the slope and the intercept for the line and find the true target vector. Since the number of examples are high, the training set is divided into a batch consisting pf 10 examples and training about 10000 batches and finds the optimum slope and intercept which has minimum  value for the loss function.
