# Tiny Models 🤏


![logo](./logos/tiny.png)


Welcome to the Tiny Models repository! This repository contains a collection of tiny models that serve as exploratory models for various tasks. These models are designed to be small and easy to understand, making them perfect for beginners who are just starting with machine learning.

# Table of Contents

1. [Variational AutoEncoder](https://github.com/Fer14/tiny_vae)
    ![logo](./logos/vae.png)
    This project demonstrates the use of a Variational AutoEncoder (VAE) to learn a latent space representation of simple synthetic data: black-and-white images of circles with varying radius, x, and y coordinates. The goal is to map these parameters to a 3-dimensional latent space, where each dimension ideally corresponds to one of the circle's properties.
2. [Diffusion Model](https://github.com/Fer14/tiny_diffusion)
    ![logo](./logos/diffusion.png)
    This project demonstrates the use of a Diffusion Model to generate synthetic data, specifically images of simple circles. The model learns to reverse a gradual noising process, starting from random noise and reconstructing meaningful images.
2. [Transformer Model](https://github.com/Fer14/tiny_transformer)
![logo](./logos/transformer.png)
This project demonstrates the use of a tiny Transformer model to perform sequence-to-sequence (seq2seq) tasks on synthetic data. The model is trained to map input sequences of symbolic tokens to corresponding output sequences, learning to predict the correct transformation of the input sequence into the desired output.