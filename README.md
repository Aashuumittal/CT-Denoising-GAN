## CT Image Denoising using CNN and GAN

A deep learning-based CT image denoising pipeline built using Convolutional Neural Networks (CNNs) and Generative Adversarial Networks (GANs). The project focuses on improving low-dose CT scan quality by reducing noise while preserving important structural details.

The model was trained on a subset of the NIH DeepLesion dataset using PyTorch and GPU acceleration on Kaggle.

---

## Project Overview

Low-dose CT scans help reduce radiation exposure but often introduce significant image noise. This project explores the use of CNN and GAN architectures to reconstruct cleaner and sharper CT images from noisy inputs.

The pipeline includes:
- CNN-based denoising
- GAN refinement using perceptual loss
- PSNR and SSIM evaluation
- Image comparison and visualization

---

## Features

- Medical image preprocessing
- CNN training pipeline
- GAN-based enhancement
- GPU-supported training
- Evaluation using PSNR and SSIM
- Visualization of denoised outputs

---

## Tech Stack

- Python
- PyTorch
- NumPy
- OpenCV
- Matplotlib
- scikit-image

---

## Dataset

This project uses the NIH DeepLesion subset dataset for experimentation and training.

Dataset structure contains:
- Clean CT images
- Artificially generated noisy images for supervised denoising

---

## Training

The workflow consists of two stages:

### 1. CNN Pretraining
The CNN model first learns the basic denoising task.

### 2. GAN Refinement
The GAN model further improves image quality and structural consistency using adversarial and perceptual learning.

---

## Evaluation Metrics

The model performance is evaluated using:
- PSNR (Peak Signal-to-Noise Ratio)
- SSIM (Structural Similarity Index)

---

## Future Improvements

- Improved visualization normalization
- Better GAN stability
- Extended dataset training

---

## Author

Ashu Mittal
