# Digit-recognition-using-GAN
This project includes digit recognition and construction using GAN. Using Generative Adversarial Network we can generate random numeric digits from 0 to 9. This repository heps one to understand the function of GAN in real world. mnist-gan is a simple GAN (Generative Adversarial Network) that learns how to generate images that look like mnist digits. Separate networks are trained for each digit. The idea is to train a "generator" network which when fed noise (in my case a 32 dimensional random vector) will generate an image that looks like an mnist style "8" (for example). In essence the network is finding a function of 32 variables that returns a matrix of pixels that look like an eight.


#Resources

Deep MNIST for Experts TensorFlow Tutorial walks you through how to train a 99+%

An Introduction to Generative Adversarial Networks A nice blog post showing a simple GAN attempting to learn a gaussian distribution with code in TensorFlow
