# From Math to Magic

> Building the mathematical and deep-learning foundations behind diffusion models — from probability and VAEs to DDPM forward diffusion using PyTorch.

**From Math to Magic** is an implementation-driven exploration of generative modeling and diffusion models.

The project starts from the mathematical foundations of probabilistic modeling and progressively builds toward the **forward diffusion process used in Denoising Diffusion Probabilistic Models (DDPMs)**.

Rather than treating diffusion models as a black box, this project focuses on understanding and implementing the underlying mathematics, latent representations, neural networks, and diffusion processes using **PyTorch**.

## 🧠 What I Built

The project covers:

- Probability and probabilistic modeling
- Gaussian distributions and Bayes' theorem
- KL Divergence and ELBO
- Variational Autoencoders (VAE)
- Convolutional VAEs
- Latent-space analysis and interpolation
- CelebA dataset preparation and preprocessing
- DDPM forward diffusion
- Linear and cosine noise schedules
- Numerical verification and visualization of the diffusion process

- ## 🛠️ Tech Stack

- **Language:** Python
- **Deep Learning:** PyTorch
- **Numerical Computing:** NumPy
- **Visualization:** Matplotlib
- **Image Processing:** Pillow, ImageIO
- **Environment:** Jupyter Notebook, Google Colab
- **Version Control:** Git, GitHub

## Overview

This repository documents my Summer of Code learning journey covering:

- Probability and Statistics
- Gaussian Distributions
- Bayes' Theorem
- KL Divergence
- Evidence Lower Bound (ELBO)
- Variational Autoencoders (VAE)
- Convolutional VAEs
- Latent Space Analysis
- Denoising Diffusion Probabilistic Models (DDPM)
- Forward Diffusion Process
- Linear and Cosine Noise Schedules
- PyTorch Implementations
## Repository Structure

```

Week0/
Week1/
Week2/
Week3/
Week4/
Week5/
Week6/
Week7/
Week8/
```

## Weekly Progress

### Week 0 – Onboarding
- Python and PyTorch fundamentals
- Neural network training workflow
- Linear regression implementation

### Week 1 – The Math of Uncertainty
- Gaussian distributions
- Bayes' theorem
- KL divergence
- Probabilistic modeling foundations

### Week 2 – ELBO and KL Divergence
- Derived and implemented KL divergence
- Verified ELBO components
- Worked with latent variable formulations

### Week 3 – Variational Autoencoder
- Implemented a fully connected VAE
- Trained on MNIST
- Visualized latent representations

### Week 4 – Convolutional VAE
- Built a ConvVAE using convolutional layers
- Generated and reconstructed MNIST digits
- t-SNE visualization of latent space
- Latent space interpolation
- β-VAE experiments
- 
  ## Week 5 – Dataset Preparation

- Prepared CelebA dataset
- Built custom PyTorch Dataset loader
- Image preprocessing
- Data pipeline setup

---

## Week 6 – Forward Diffusion Implementation

- Implemented reusable ForwardDiffusion class
- Linear beta schedule
- Cosine beta schedule
- Closed-form forward diffusion equation

---

## Week 7 – Numerical Verification & Visualization

- Verified forward diffusion mathematically
- Generated diffusion trajectory
- Created destruction GIF
- Visualized gradual image corruption

---

## Week 8 – Noise Schedule Comparison

- Compared Linear vs Cosine schedules
- Studied effect on image degradation
- Completed reusable notebook for forward diffusion pipeline



- ## Project Status

Current Progress: Week 8 / Week 13

Completed:

- Mathematical foundations
- Variational Autoencoders
- Forward Diffusion Process
- Noise Schedule Analysis

Upcoming Work:

- Reverse Diffusion
- U-Net implementation
- Noise Prediction Network
- Image Generation

- ## Conclusion

This repository documents my Summer of Code journey from foundational probability concepts to implementing the forward diffusion process used in DDPMs. Throughout the first eight weeks, I progressively built the theoretical understanding and practical implementation required for diffusion models. The remaining weeks will focus on reverse diffusion, neural network training, and image generation to complete the full DDPM pipeline.

## Author

**Diptanshu Raut**  
B.Tech Chemical Engineering, IIT Bombay
