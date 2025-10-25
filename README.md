# Brain-Tumor-Classification-using-FFT-and-DWT
This repository presents a **Brain Tumor Classification System** that classifies MRI images into four types of tumors — *Glioma, Meningioma, Pituitary*, and *Normal* — using advanced **image processing** and **machine learning** techniques.  
The project leverages **Discrete Wavelet Transform (DWT)**, **Fast Fourier Transform (FFT)**, **GLCM (Gray Level Co-occurrence Matrix)**, and **LBP (Local Binary Pattern)** for hybrid feature extraction, combined with a **PyTorch-based Multi-Layer Perceptron (MLP)** classifier for high accuracy.

## 🩻 Sample Brain MRI Images

The following image demonstrates MRI scans of different brain tumor types used in this project.

<p align="center">
  <img src="Img/Tumors Images.png" alt="Brain Tumor MRI Samples" width="512" />
</p>

## 🚀 Project Overview

This project explores a hybrid feature extraction technique for medical image classification.  
MRI images often contain both **texture** and **frequency** details that are crucial for accurate diagnosis.  
To capture these, this model integrates multiple transformations and statistical feature extractors.

### 🧩 Key Components:
- **FFT (Fast Fourier Transform):** Extracts frequency domain information.
- **DWT (Discrete Wavelet Transform):** Captures both time and frequency features.
- **GLCM (Gray Level Co-occurrence Matrix):** Measures texture contrast and correlation.
- **LBP (Local Binary Pattern):** Detects micro-textures and edges.
- **CLAHE (Contrast Limited Adaptive Histogram Equalization):** Enhances image contrast for better feature extraction.
