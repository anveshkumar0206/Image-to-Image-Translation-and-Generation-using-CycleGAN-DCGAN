# Image-to-Image-Translation-and-Generation-using-CycleGAN-DCGAN

The project demonstrates image-to-image translation and unsupervised image generation using PyTorch.

Project Overview

This project explores two advanced Generative Adversarial Networks (GANs):

1.CycleGAN – Used for style transfer between Monet paintings and real-world photos.
2.DCGAN – Used for generating images from random noise.

Dataset

CycleGAN: Uses the Monet-to-Photo dataset, which consists of Monet paintings and real-world photographs.

DCGAN: Uses Fashion MNIST or other datasets for generating synthetic images.

Model Training Workflow

1. CycleGAN Implementation (Image-to-Image Translation)
Load the Monet-to-Photo dataset.
Train CycleGAN to learn the mapping between Monet paintings and real-world images.
Convert test images using the trained model.
Apply CycleGAN on a custom image (e.g., your picture).

2. DCGAN Implementation (Deep Convolutional GAN)
Load the Fashion MNIST dataset.
Train a DCGAN model to generate realistic images.
Experiment with different parameters and architectures.
Compare results with different training epochs.

Results

Comparison between CycleGAN Monet-to-Photo conversion vs. original images, and
Generated images from DCGAN.
Analysis of training stability and improvements in image quality.
