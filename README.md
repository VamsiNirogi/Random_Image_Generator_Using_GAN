# Random_Image_Generator_Using_GAN
This project implements a Generative Adversarial Network (GAN) using PyTorch to generate realistic images from random noise. The model is trained on a dataset of flower images, learning to create visually appealing synthetic images. The project includes data preprocessing, model training, loss visualization, and image generation.

# Overview
This project implements a GAN to generate realistic 64x64 pixel images. The model consists of a generator that synthesizes images from random noise and a discriminator that differentiates between real and generated images.

# Installation
1.Install required dependencies: pip install torch torchvision numpy matplotlib pillow 

2.Clone the repository: https://github.com/VamsiNirogi/Random_Image_Generator_Using_GAN/tree/main

# Dataset
The project requires a dataset of images for training. Get data from Kaggle

Update the text_file and image_data_dir variables in the script to point to your dataset.

# Usage
1.Run the training script: python train.py

2.Generated images will be saved periodically during training.

3.After training, use the saved model to generate new images.

# Training Details
Loss Function: Binary Cross-Entropy (BCE Loss)

Optimizer: Adam (β1 = 0.8, β2 = 0.999)

Learning Rate: 0.0002

Epochs: 500

Batch Size: 128

# Results
The model generates visually realistic images over multiple epochs.

Training progress can be monitored through loss plots.

# Future Improvements
Implement convolutional GANs (DCGAN) for higher-quality images.

Experiment with different datasets.

Fine-tune hyperparameters for better results.
