# Denoising Diffusion Probabilistic Model (DDPM) Implementation

This repository contains a Google Colab notebook with an implementation of the **Denoising Diffusion Probabilistic Model (DDPM)**. This project was part of my university bachelor thesis, where I explored the theory and application of DDPMs, a type of generative model that has gained popularity for generating high-quality images. The model is similar in nature to score-based generative models.

## Features

- **Forward Diffusion Process**: Gradually adds Gaussian noise to data over a sequence of time steps.

- **Reverse Diffusion Process**: Trains a model to denoise and recover the original data from noisy data.

- **Flexible Architecture**: The implementation uses a U-Net-based architecture for denoising.

- **PyTorch Implementation**: The entire code is implemented in PyTorch, making it easy to run on both CPU and GPU.

- **Google Colab Friendly**: The notebook is ready to be run on Google Colab for easy execution and experimentation.
