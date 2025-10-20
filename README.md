# autoencoders-vae-tutorial
 A practical tutorial on Autoencoders, Convolutional Autoencoders, and Variational Autoencoders using PyTorch — includes theory, code, and visualization on the MNIST dataset.

# 🧠 Autoencoders & Variational Autoencoders (VAE) Tutorial

This repository contains a comprehensive notebook that demonstrates how **Autoencoders**, **Convolutional Autoencoders (CAE)**, and **Variational Autoencoders (VAE)** work — both theoretically and practically — using the **MNIST** dataset.

---

## 📘 Overview

An **Autoencoder** is a type of neural network that learns to compress and reconstruct data, typically used for:
- Dimensionality reduction
- Denoising
- Anomaly detection
- Feature extraction

This notebook walks through:
1. The theoretical foundations of Autoencoders  
2. Building and training a **Convolutional Autoencoder (CAE)**  
3. Implementing a **Variational Autoencoder (VAE)**  
4. Visualizing reconstruction quality and comparing results  

---

## 🧩 Model Comparison

| Model | Key Idea | Strength | Best For |
|-------|-----------|-----------|-----------|
| **Autoencoder (AE)** | Encodes & decodes images directly | Simple, efficient reconstruction | Denoising / compression |
| **Convolutional AE (CAE)** | Uses Conv layers to capture spatial patterns | Sharp reconstructions | Image data |
| **Variational AE (VAE)** | Learns structured latent distributions | Generates new samples | Generative tasks |

---

## 🧑‍💻 Implementation

The notebook is written in **PyTorch** and trains both models for 5 epochs on the MNIST dataset.

```bash
# Clone this repository
git clone https://github.com/<your-username>/autoencoders-vae-tutorial.git
cd autoencoders-vae-tutorial

# Open in Google Colab or Jupyter

Visualization
The final comparison shows:

Original Images

Reconstructed by CAE

Reconstructed by VAE

CAE images appear sharper, while VAE results are smoother but more generative.

 Key Learning Outcomes
Understand the structure and math of Autoencoders

Learn how to build and train them using PyTorch

Compare AE vs VAE in terms of reconstruction and generation

Visualize latent space representations using t-SNE

 License
MIT License © 2025 Ghaida Al-Luhaiby

✨ Author
Ghaida Al-Luhaiby
Master’s Student — Computer Science & AI, Umm Al-Qura University
📧 Ghaida1517@gmail.com
