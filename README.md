# Predicting-Mortality-Rate-Using-ANN
Artificial Neural Network Tutorial provides basic and advanced concepts of ANNs. Our Artificial Neural Network tutorial is developed for beginners as well as professions.

The term "Artificial neural network" refers to a biologically inspired sub-field of artificial intelligence modeled after the brain. An Artificial neural network is usually a computational network based on biological neural networks that construct the structure of the human brain. Similar to a human brain has neurons interconnected to each other, artificial neural networks also have neurons that are linked to each other in various layers of the networks. These neurons are known as nodes.

Artificial neural network tutorial covers all the aspects related to the artificial neural network. In this tutorial, we will discuss ANNs, Adaptive resonance theory, Kohonen self-organizing map, Building blocks, unsupervised learning, Genetic algorithm, etc.

### How do artificial neural networks work?
Artificial Neural Network can be best represented as a weighted directed graph, where the artificial neurons form the nodes. The association between the neurons outputs and neuron inputs can be viewed as the directed edges with weights. The Artificial Neural Network receives the input signal from the external source in the form of a pattern and image in the form of a vector. These inputs are then mathematically assigned by the notations x(n) for every n number of inputs.

Afterward, each of the input is multiplied by its corresponding weights ( these weights are the details utilized by the artificial neural networks to solve a specific problem ). In general terms, these weights normally represent the strength of the interconnection between neurons inside the artificial neural network. All the weighted inputs are summarized inside the computing unit.

If the weighted sum is equal to zero, then bias is added to make the output non-zero or something else to scale up to the system's response. Bias has the same input, and weight equals to 1. Here the total of weighted inputs can be in the range of 0 to positive infinity. Here, to keep the response in the limits of the desired value, a certain maximum value is benchmarked, and the total of weighted inputs is passed through the activation function.

The activation function refers to the set of transfer functions used to achieve the desired output. There is a different kind of the activation function, but primarily either linear or non-linear sets of functions. Some of the commonly used sets of activation functions are the Binary, linear, and Tan hyperbolic sigmoidal activation functions.

### Perceptron:
It is single layer Neural Network. The single layer neural network perceptron is applicable for linearly seperable data.It calculated weighted sum of inputs values.The perceptron outputs non zero value only when weighted sum exceeds a certain threshold value.If we consider two inputs as (x,y) on a plane,then perceptron tells us which region on plane to which this points belongs.Such regions are linearly seperable regions.

If data is not linearly seperable we need more than one perceptron.

The information is constantly fed forward from one layer to the next thus this networks are also called feed forward network

### Back propogation:
The goal of back propogation in neural networks is to optimize the weights so weights so that the neural network can learn how to correctly map arbitrary inputs and outputs

Options that are empirically determined in Neural network:

- Number of Hidden Layers.
- Number of neurons in each hidden layer
- Activation Function
- Error/Loss Function
- Gradient descent methods.

### Convolution Neural Networks:-
Convolution Neural Network (CNN) are powerful artificial neural network technique.It preserve the spatial structure of the problem and were developed for object recognition task such as handwritten digit recognition.There are three types of layers in convolution neural network:- a) Convolution layers. b) Pooling layers. c) Fully Connected layers.

Using keras tuner we can decide about how many layers to use, how many neurons to use, what activation function to use that is which of them will give the best model.


