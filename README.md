# NN_Assignmnet_4
# 🧠 CS5720 – Home Assignment 4

## University of Central Missouri  
**Course**: Neural Networks and Deep Learning  
**Instructor**: Dr. I-Hua Tsai  
**Student Name**: *Jagarlamudi Tharaka*  
**Semester**: Summer 2025  

---

## 📘 Overview

This repository contains the implementation and demonstration of **Home Assignment 4**, focused on:
- Generative Adversarial Networks (GANs)
- Data Poisoning Attacks on Sentiment Classifiers

All experiments are conducted using **Google Colab**.

---

## 🧪 Tasks

### ✅ Task 3: Basic GAN on MNIST
- **Tool**: TensorFlow 2.x (Keras)
- **Dataset**: MNIST Handwritten Digits
- **Implementation**:
  - Generator and Discriminator network design
  - Adversarial training loop with alternating updates
  - Image generation at Epochs `0`, `50`, and `100`
  - Visualization of Generator vs Discriminator loss

### 🧨 Task 4: Data Poisoning Simulation *(WIP)*
- Simulate a label-flipping attack on sentiment classification
- Visualize accuracy and confusion matrix:
  - Before poisoning
  - After poisoning

---

## 📁 Files in this Repository

| File Name                                 | Description                              |
|------------------------------------------|------------------------------------------|
| `Home_Assignment_4.ipynb` | Main Colab Notebook for Tasks 3 & 4       |
| `README.md`             | This GitHub-style documentation           |
| `image_at_epoch_000.png` *(output)*       | Sample GAN image at start                 |
| `image_at_epoch_050.png` *(output)*       | Sample GAN image after 50 epochs          |
| `image_at_epoch_100.png` *(output)*       | Final GAN result after 100 epochs         |

---

## ▶️ Running on Google Colab

1. Download the `.ipynb` notebook from this repo.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload and open the notebook.
4. Run all cells sequentially.
5. Output images and loss curves will be auto-generated.

---

## 📊 Sample Output

### ✅ Generated Images

Images are saved and displayed after:
- Epoch 0
- Epoch 50
- Epoch 100

### 📉 Loss Curve

Includes plot comparing Generator and Discriminator losses.
