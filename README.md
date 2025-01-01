# CNN Forward Pass and Backpropagation from Scratch

This project implements a Convolutional Neural Network (CNN) forward pass and backpropagation from scratch. The implementation includes the following key operations:

## Features

1. **Forward Pass**:
   - **2D Convolution Operation**: Perform convolution with a single filter.
   - **ReLU Operation**: Apply the ReLU activation function.
   - **MaxPooling Operation**: Downsample the feature map using max pooling.
   - **Flatten Operation**: Flatten the output of the max pooling layer.
   - **Fully Connected Layer**: Pass the flattened data through a dense layer.
   - **Softmax Operation**: Compute class probabilities using softmax.
   - **Cross-Entropy Loss Function**: Calculate the loss for classification tasks.

2. **Backpropagation**:
   - Compute gradients manually from the loss to filters.
   - Currently supports backpropagation for a single filter.

## Issues

- **Filter Backpropagation**: The current implementation only supports backpropagation for a single filter. 

## To-Do

- Extend the backpropagation to handle multiple filters during the convolution operation.
- Input gradients for the convolution operation
