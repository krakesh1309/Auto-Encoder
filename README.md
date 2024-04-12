An Autoencoder
An autoencoder is a type of artificial neural network used to learn data encodings in an unsupervised manner.
The aim of an autoencoder is to learn a lower-dimensional representation (encoding) for a higher-dimensional data, typically for dimensionality reduction,
by training the network to capture the most important parts of the input image.

The architecture of autoencoders
Autoencoders consist of 3 parts:
1. Encoder: A module that compresses the train-validate-test set input data into an encoded representation that is typically several orders of magnitude smaller than the input data.

2. Bottleneck: A module that contains the compressed knowledge representations and is therefore the most important part of the network.

3. Decoder: A module that helps the network“decompress” the knowledge representations and reconstructs the data back from its encoded form. The output is then compared with a ground truth.

Import necessary libraries
For the implementation, we are going to import matplotlib, numpy, pandas, sklearn and keras.
