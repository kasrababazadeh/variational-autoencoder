# Variational Autoencoder (VAE)

This repository contains an implementation of a Variational Autoencoder (VAE) using the PyTorch framework. The VAE is trained on the MNIST dataset, which consists of handwritten digits. The model learns to encode input images into a latent space and then decode them back, allowing for image generation and reconstruction.

## Features

- Encoder-Decoder architecture
- Utilizes convolutional layers for feature extraction
- Trains on the MNIST dataset
- Implements the reparameterization trick for latent variable sampling
- Visualizes reconstructed images and latent space interpolation

## Requirements

- Python 3.x
- PyTorch
- torchvision
- matplotlib

You can install the required packages using pip:

```bash
pip install torch torchvision matplotlib
```

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/kasrababazadeh/variational-autoencoder.git
   cd variational-autoencoder
   ```

2. **Run the Jupyter Notebook:**

   ```bash
   jupyter notebook variational-autoencoder.ipynb
   ```

3. **Follow the instructions in the notebook to train the VAE and visualize the results.**

## Training

The model is trained for 30 epochs with a batch size of 128. You can adjust the hyperparameters in the notebook as needed.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
