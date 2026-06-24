## Project Overview

This notebook covers a complete MNIST classification workflow using PyTorch:

- Set up device selection for GPU, MPS, or CPU
- Load and normalize the MNIST training and test datasets
- Inspect and display a sample MNIST image with helper utilities
- Build a simple neural network with a flattened input, one hidden layer, and ReLU activation
- Train the model using `CrossEntropyLoss` and the `Adam` optimizer
- Track epoch-wise training loss and test accuracy
- Evaluate performance on the held-out MNIST test set
- Display predictions and plot training metrics
