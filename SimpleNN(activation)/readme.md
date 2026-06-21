## Project Overview

The notebook demonstrates the basic PyTorch workflow:

- Import helper utilities and set the random seed
- Create a combined delivery dataset of distances and times
- Normalize the input and target tensors
- Build a neural network with one hidden layer and ReLU activation
- Train the model using Mean Squared Error loss and SGD optimizer
- Plot training progress and the final fitted result
- Predict delivery time for a new distance and decide whether to use a bike or car
