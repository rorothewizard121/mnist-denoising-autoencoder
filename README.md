# MNIST-denoising-autoencoder
NumPy Implementation of a Dense Denoising Autoencoder for the MNIST Dataset.  
With this project I wanted to implement a simple denoising autoencoder from the bottom up using only NumPy.
This project is part of my machine learning journey, and the goal was mainly to better understand the workings
of the DAE architecture and also deepen my understanding of the math behind it.

The model is not tuned and optimized, as can be seen in the training example, but I have included the most important features, namely:
- Noise injection
- The encoder-decoder architecture
- Image reconstruction

Despite poor results on reconstruction of the digits, the model does manage to remove substantial amounts of noise from images.

## Libraries used:
- tensorflow.keras.datasets (only for importing the MNIST dataset)
- matplotlib.pyplot (for plotting images)
- NumPy

## Features:
- Customizable sequential architecture (inspired by Keras)
- Noise injection
- Training and reconstruction pipeline
- Visualization of results

## Limitations:
- Trained using CPU, my current GPU is GTX 680 and lacks modern support for GPU acceleration
- Good reconstruction is also limited by the model depth and tuning

