# MNIST dataset neural network
This neural network is made for the MNIST dataset which contains 
60,000 training and 10,000 testing images of handwritten digits.

![The dataset.](https://i.imgur.com/wVYEMTk.png)

# Dataset
You can find the MNIST dataset [here](http://yann.lecun.com/exdb/mnist/).

# Accuracy
These are two benchmarks ran on my machine.

No GPU was used, it should be interesting to see the training time
when a GPU is used.
- 97.75% (12 minutes):
    - 20 epochs
    - 0.02 learning rate
    - 300 hidden nodes
- 97.13% (4 minutes):
    - 5 epochs
    - 0.1 learning rate
    - 300 hidden nodes

# Try your own handwriting
Draw on a 28x28 png. Make sure to center the digit and make it averagely sized.

`three.png` is my example, you can replace it.

This neural network wasn't trained on preprocessed images (moved, rotated, sharpened, blurred, etc).
![An example of my own handwriting](https://i.imgur.com/6QacnX4.png)
