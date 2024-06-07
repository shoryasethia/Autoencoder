# Autoencoders

| Autoencoder | Notebook | ckpts | MSE |
|-------------|----------|----------------------|-----|
|Vanilla autoencoder|[.ipynb](https://github.com/shoryasethia/Autoencoder/blob/main/VanillaAutoEncoder.ipynb)|[🔗](https://github.com/shoryasethia/Autoencoder/tree/main/checkpoints/VanillaAutoEncoder)|0.014516565627219851|
|Deep Convolutional autoencoder|[.ipynb](https://github.com/shoryasethia/Autoencoder/blob/main/DCAutoEncoder.ipynb)|[🔗]()|0.00950322496098459|

> **For all autoencoders, I have used tensorflow, keras and MNIST Dataset**
_________________________________________________________________________________________________________________________________________________
Autoencoders are a type of neural network used for **unsupervised learning**. Autoencoders consist of an **encoder** which processes the input into **some latent features** and a **decoder** which uses those latent features and tries to reconstruct the original image, they work together to learn an efficient representation of the input data.

### Architecture

The architecture of an autoencoder typically consists of an `input layer`, a `hidden layer (encoder)`, and an `output layer(decoder)`. The encoder compresses the input data into a latent space representation, while the decoder reconstructs the original input from the latent space representation.

### Training

During training, the autoencoder learns to **minimize** the reconstruction error between the input and the output. This is achieved by optimizing the weights of the neural network using backpropagation and gradient descent.

### Loss Function

The loss function used for training autoencoders depends on the type of data and the objective of the model. Common loss functions I used while training include mean squared error (MSE) for continuous data and binary cross-entropy for binary data.

