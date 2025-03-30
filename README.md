<img src='https://github.com/suneelmeesalameher/GAN_SHIRT/blob/main/gan_generated_images.gif'>

# GAN-based Image Generation from Fashion MNIST

This repository contains code to implement a Generative Adversarial Network (GAN) for generating images of shirts from the Fashion MNIST dataset. The GAN consists of a generator that creates new images from random noise and a discriminator that distinguishes between real and fake images. The generator and discriminator are trained simultaneously in a zero-sum game until the generator produces realistic images.



## Introduction

Generative Adversarial Networks (GANs) are a class of machine learning frameworks designed by Ian Goodfellow and his colleagues in 2014. GANs consist of two neural networks, the generator and the discriminator, which compete against each other in a zero-sum game. The generator creates new data instances, while the discriminator evaluates them for authenticity.

This project demonstrates the implementation of a GAN to generate images of shirts from the Fashion MNIST dataset using TensorFlow and Keras.

## Requirements

To run the code, you'll need the following libraries:

- numpy
- pandas
- matplotlib
- seaborn
- tensorflow
- keras
- imageio

## 🧠 Learnings & Highlights

- Gained hands-on experience with adversarial training dynamics  
- Explored convergence techniques for image quality improvements  
- Understood trade-offs in generator/discriminator architecture tuning  
- Implemented visualization tools to monitor model performance over time  

## 🪄 Future Work

- Explore Conditional GANs (cGAN) to generate all 10 Fashion MNIST classes  
- Improve image resolution with DCGAN or StyleGAN extensions  
- Add evaluation metrics like FID (Fréchet Inception Distance) 

## 🤝 Contributing

Feel free to fork and improve! Open to suggestions and contributions.
