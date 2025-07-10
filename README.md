# Task 04 – Image Generation using cGAN on CIFAR-10  
**Track Code:** GA | **Repo:** PRODIGY_GA_04

This project explores the use of **Conditional Generative Adversarial Networks (cGANs)** for image generation on the **CIFAR-10** dataset. Instead of the typical pix2pix approach using paired datasets, this model generates images based on class labels, allowing the GAN to conditionally synthesize visuals from scratch.

---

## 🌐 Project Summary

In this version of Task 04, I implemented a conditional GAN that:
- Conditions the generator on **image class labels (0–9)**  
- Generates **32x32 images** similar to those in the CIFAR-10 dataset  
- Learns the mapping from noise + label → realistic image

---

## 🔍 Key Concepts

- Conditional adversarial training  
- Image generation using GANs from label input  
- One-hot encoding class labels for conditional control  
- Discriminator loss balancing and generator feedback

---

## 📁 Repository Contents

- `cGAN_CIFAR10_Image_Generation.ipynb` – Colab notebook for training and visualization  
- `README.md` – This documentation

---

## 🧠 What I Learned

- Working with image datasets in PyTorch  
- Architecting generator and discriminator networks for cGAN  
- Training GANs with label conditions  
- Visualizing multi-class image generation dynamically

---

## 🛠️ Stack & Tools

- Python  
- PyTorch  
- Google Colab  
- CIFAR-10 dataset  
- Matplotlib, torchvision

---

## 🎯 Internship Info

> **Completed as part of:**  
> Prodigy InfoTech – Generative AI Internship  
> **Duration:** June–July 2025  
>  
> #ProdigyInfoTech #GenerativeAI #cGAN #ImageGeneration #CIFAR10 #AIInternship #PyTorch
