# Build a Generative Adversarial Network in PyTorch

The purpose of this repository is to build a Generative Adversarial Network (GAN) deep learning model in PyTorch using MNIST image dataset. It consists of two models: generator model and discriminator model. Generator model generates fake images which look like real images, and discriminator model classifies the fake and real images.

In short, this repository performs the following operations:
1. Loading the MNIST image dataset and exploring it along with visualization
2. Loading dataset into batches
3. Creating the discriminator network model
4. Creating the generator network model
5. Defining loss functions and optimizers for both models
6. Train both models simultaneously
7. Visualizing fake images generated by generator model
