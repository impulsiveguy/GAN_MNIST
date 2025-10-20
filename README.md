# MNIST GAN — Handwritten Digit Generator

This project implements a **Generative Adversarial Network (GAN)** to generate **MNIST-style handwritten digits** using **TensorFlow/Keras**.  
It includes a full **training pipeline**, **checkpoint management**, **image grid visualization**, and a **Streamlit web app** for interactive generation.

---

## Overview

The goal of this project is to train a **Deep Convolutional GAN (DCGAN)** on the **MNIST dataset** and generate new, realistic handwritten digits.  
The GAN consists of:
- A **Generator** that learns to produce fake MNIST-like images from random noise.
- A **Discriminator** that learns to distinguish between real and generated images.

After training, the generator model can be loaded into the Streamlit app to create digits on demand.

---

## Features

- Fully functional **GAN architecture** with configurable latent dimension  
- **Custom training loop** using TensorFlow  
- **Checkpoint saving and resuming** of model training  
- **Label smoothing** and stable **Adam optimizer** training  
- **Image grid visualizations** after each epoch  
- **Streamlit web app** to generate and visualize new digits in real-time  
- Modular code with separate files for:
  - Model definition (`mnist_model.py`)
  - Training (`train_mnist.py`)
  - Utilities (`utils.py`)
  - Web app (`app.py`)

---

## Dependencies

Install all required packages using:
pip install tensorflow keras numpy pandas matplotlib streamlit


