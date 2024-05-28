# building a simple neural network from scratch
# Number (digit) Recognizer

- Simple MNIST NN from scratch¶
In this notebook, I implemented a simple two-layer neural network and trained it on the MNIST digit recognizer dataset. It's meant to be an instructional example, through which you can understand the underlying math of neural networks better.

Our NN will have a simple two-layer architecture. Input layer  𝑎[0]
  will have 784 units corresponding to the 784 pixels in each 28x28 input image. A hidden layer  𝑎[1]
  will have 10 units with ReLU activation, and finally our output layer  𝑎[2]
  will have 10 units corresponding to the ten digit classes with softmax activation.
