# 🧼 Denoise MNIST using Autoencoder

This project implements an image denoising model using a deep autoencoder trained on the MNIST dataset.

The goal is to remove noise from corrupted handwritten digit images and reconstruct clean versions.

## 📌 Project Overview

Noise is artificially added to MNIST digit images.
A neural network (Autoencoder) is trained to learn how to reconstruct the original clean images from noisy inputs.

This demonstrates:

- Image preprocessing
- Noise injection
- Deep learning model design
- Encoder–Decoder architecture
- Model training and evaluation
- Image reconstruction

## 🧠 Model Architecture

The model uses an Autoencoder structure:

Encoder:
- Dense layers with nonlinear activation
- Latent representation compression

Decoder:
- Dense layers
- Reconstruction to original image size (28x28)

Loss Function:
- Mean Squared Error (MSE)

Optimizer:
- Adam

## 📊 Dataset

- MNIST handwritten digits dataset
- Image size: 28x28 grayscale
- Normalized to range [0,1]

## 🚀 How to Run

1. Clone the repository:
https://github.com/c-ehsan/denoise_mnist.git
