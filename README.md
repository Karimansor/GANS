# Generative Adversarial Network (GAN) for Image Generation

This notebook implements a **Generative Adversarial Network (GAN)** to generate images.

It uses a dataset of images—likely of faces with and without masks—based

### Features:
- **Discriminator and Generator models** are defined and trained.
- Training is handled by custom functions: `train_discriminator` and `train_generator`.
- **Visualizations** include:
  - Losses of both the discriminator and generator
  - Discriminator scores over training epochs

### Purpose:
The goal is to train a GAN that can learn and mimic the distribution of input images, effectively generating new images similar to the original dataset.
