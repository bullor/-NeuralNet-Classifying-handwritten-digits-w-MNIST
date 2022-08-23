# -NeuralNet-Classifying-handwritten-digits-w-MNIST
[NeuralNet]Classifying handwritten digits with MNIST dataset

# Classifying handwritten digits with MNIST Dataset

In this notebook , I implemented a simple multilayer neural network from scratch using GradientDecent that can classify MNIST dataset handwritten digits instead of using an open source Python machine learning library.I have connected multiple neurons to a powerful NN architecture to solve complex problems such as handwritten digit recognition.

Below steps were applied through model build-up :

- Download the MNIST Data Set
- Normalize the Data to let algorithm behave more stable under GradientDecent optimization
- Define (layer_number=2, hidden_neuron_number=50) NeuralNetMLP Class to implement forward and backward passes for execution.
- Train the model with parameters num_epochs = 50 and minibatch_size = 100 and learning_rate = 0,1
- Define loss and accuracy functions
- Plot Accuracy and Cost function.
- Output 25 misclassified example those were predicted incorrectly in test set.

The MNIST dataset is publicly available at http://yann.lecun.com/exdb/mnist/ and consists of the following four parts:

- Training set images: train-images-idx3-ubyte.gz (9.9 MB, 47 MB unzipped, 60,000 examples)
- Training set labels: train-labels-idx1-ubyte.gz (29 KB, 60 KB unzipped, 60,000 labels)
- Test set images: t10k-images-idx3-ubyte.gz (1.6 MB, 7.8 MB, 10,000 examples)
- Test set labels: t10k-labels-idx1-ubyte.gz (5 KB, 10 KB unzipped, 10,000 labels)
