# Handwriting Recognize
A small project I made to hone my understanding about neural network. 

## Problem
Given a grayscale 28x28 pixel image. We need to predict which digit is it from the image. 

## Solution
I use a neural network consists of 3 layers: 1 input layer, 1 hidden layer, 1 output layer.

### Input layer 
Contains 784 neurons (stands for 784 pixels of an example image)

### Hidden layer
I choose a hidden layer with the size of 16 neurons.

### Output layer
Output layer has 10 neurons, which neuron has the brightest (highest) activation is the output of the network. 

### Activation function
Sigmoid function