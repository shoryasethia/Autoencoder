# Autoencoders

| Autoencoder | Notebook | ckpts | MSE |
|-------------|----------|----------------------|-----|
|Vanilla autoencoder|[.ipynb](https://github.com/shoryasethia/Autoencoder/blob/main/VanillaAutoEncoder.ipynb)|[🔗](https://github.com/shoryasethia/Autoencoder/tree/main/checkpoints/VanillaAutoEncoder)|0.014516565627219851|
|Deep Convolutional autoencoder|[.ipynb](https://github.com/shoryasethia/Autoencoder/blob/main/DCAutoEncoder.ipynb)|[🔗](https://github.com/shoryasethia/Autoencoder/tree/main/checkpoints/DCAutoEncoder)|0.00950322496098459|

> **For all autoencoders, I have used tensorflow, keras and MNIST Dataset**
_________________________________________________________________________________________________________________________________________________

### Clone this repo by
```
git clone https://github.com/shoryasethia/Autoencoder
cd Autoencoder
```
_________________________________________________________________________________________________________________________________________________
Autoencoders are a type of neural network used for **unsupervised learning**. Autoencoders consist of an **encoder** which processes the input into **some latent features** and a **decoder** which uses those latent features and tries to reconstruct the original image, they work together to learn an efficient representation of the input data.

### Architecture

The architecture of an autoencoder typically consists of an `input layer`, a `hidden layers (encoder)`, and an `output layer(decoder)`. The encoder compresses the input data into a latent space representation, while the decoder reconstructs the original input from the latent space representation.

> If this repo helped in any way, star this repo.
**Author : [@shoryasethia](https://github.com/shoryasethia)**
