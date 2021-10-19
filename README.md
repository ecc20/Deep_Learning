# Deep_Learning

## Deep Learning Coursework at Imperial College London

**Packages:** PyTorch, scikit-learn

### CW1: Convolutional Neural Networks
* Built from scratch the following types of layers: 2D convolution, max pooling, and linear. Also constructed 2d batch normalization
* Implemented a ResNet-18 architecture to perform classification on the CIFAR-10 dataset. 

### CW2: VAE and GAN
**Divided in two parts:**
* The first part consists in a variational autoencoder used in the MINST dataset. In adition to the implementation, the following is shown or discussed

Reconstruction samples and a few generated samples are shown

How does the loss function relate to the VAE prior, the output data domain, and disentanglement in the latent space

Behaviour of the log-likelihood loss and the KL loss by observing their graphs

Posterior collapse

Role of the KL loss term and 𝛽 in the latent representation of the test set (visualized using T-SNE)

Interpolation in the latent space is shown

* The second part consists of a Deep Convolutional GAN implementation in the CIFAR-10 dataset. Some important features of the implementation are:
Batch normalisation

ReLU activation in the generator, and Leaky ReLU activation in the discriminator

Data augmentation - RandomCrop and RandomHorizontalFlip

The following topics are discussed in the second part:
Generator and discriminator's loss curves

Mode collapse

### CW3: RNNs
Implementation:
* LSTM cell
* Vanilla cell
* GRU cell
* Regular RNN model
* Bidirectional RNN model

Theory:
* What is the vanishing gradients problem and why does it occur? Which activation functions are more or less impacted by this, and why?
* Why do LSTMs help address the vanishing gradient problem compared to a vanilla RNN?
* By observing 3 training curves (epochs vs. performance), which curve belongs to each type of RNN (vanilla, GRU, and LSTM)?
* When might you choose to use each of the three different types of models (vanilla, GRU, LSTM)?


