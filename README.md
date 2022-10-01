# Variational Autoencoder and Generative Adversarial Network

In this project we aim to implement variational autoencoder and generative adversarial network on MNIST dataset. We will first derive the VAE algorithm and then implement the training and inference algorithms for VAE. We further experiment the VAE model with different number of nodes in the bottleneck layer in the middle of encoder-decoder architecture. Next we have implemented Convolution Neural Network for encoder and Deconvolution neural network for decoder.

We then derive the Generative Adversarial Network algorithm and then implemented the algorithm to train on MNIST data to generate the digits. We have first created the generator model with 3 dense layers and LeakyRelu activation function. Then we have created the discriminator model with 3 dense layer and LeakyRelu activation function. 
During training, we freeze the generator while training the discriminator and discriminator tries to figure out how to distinguish real data from fake data. Similarly, we keep the disciminator constannt during the generator phase, this back and forth training allows GANs to tackle intractable generative problems. 


# Dataset
The dataset that was used for this project was MNIST dataset.

