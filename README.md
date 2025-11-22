# 🛰️ CubeSat Image Classification - Hack4dev Hackathon 2025

## 📋 Project Overview

This repository contains one of the winning solution for the **Hack4dev International Hackathon 2025** - a 4-day intensive competition (April 7-10, 2025) focused on developing efficient deep learning models for CubeSat image classification. Our team achieved **top-20 international ranking** among competitive global participants.

### 🎯 Competition Challenge
The VERTECS mission aims to study extragalactic radiation using CubeSats with severe constraints:
- **Limited onboard memory** and computational power
- **Restricted data transfer bandwidth**
- **Need for real-time image prioritization** before transmission to Earth

**Objective:** Develop an optimized CNN model to classify satellite images into five categories with maximum efficiency and accuracy.


### File Details in this Repository:

- **`Model_Cnn.ipynb`** - Main Jupyter notebook containing:
  - Complete data preprocessing pipeline
  - CNN model architecture and training code
  - Performance evaluation and visualization
  - Resource monitoring and optimization techniques

- **`Model_Cnn.h5`** - Pre-trained optimized model:
  - 99.9% test accuracy
  - Only 0.05 MB file size
  - Ready for immediate inference
  - TensorFlow/Keras compatible

- **`Final_Competition_Report.pdf`** - Detailed competition report:
  - Methodology and architectural decisions
  - Performance analysis and benchmarks
  - Technical innovations and optimizations
  - Deployment recommendations

## 🏆 Achievement
- **🏅 Top 20 International Ranking** in competitive evaluation
- **⚡ 24x faster** inference than baseline model (11.01s vs 265.27s)
- **📦 23x smaller model size** (0.05 MB vs 1.16 MB)
- **🎯 99.9% accuracy** on test dataset across all classes

## 🎪 Hackathon Context & Original Challenge

### Competition Framework
This project was developed during the **Hack4dev CubeSat Image Classification Challenge**, which provided a structured framework through five comprehensive notebooks:

#### 📓 Official Hackathon Notebooks:
[**Official Hackathon Repository**](https://github.com/Hack4Dev/CubeSat_ImageClassify?tab=readme-ov-file)

1. **Notebook 1**: Introduction to the problem and hackathon overview
2. **Notebook 2**: Reading and analyzing astronomical data
3. **Notebook 3**: Classification using traditional machine learning models
4. **Notebook 4**: Classification using deep learning models
5. **Notebook 5**: Comprehensive model evaluation

## 🔗 Important Links & Resources

### 🎯 Official Competition Resources
- **Research Paper**: [arXiv:2408.14865](https://arxiv.org/pdf/2408.14865)
- **Dataset Source**: [Zenodo Repository](https://zenodo.org/records/14598875)

### 📚 Educational Materials
- **Essential Pre-competition Watching**: [Tutorial Video](https://www.youtube.com/watch?v=3N9-eGfQiS0) - Prof. Thron's comprehensive guide to problem understanding and solution approaches
- **Original Research**: [SPIE Proceedings](https://doi.org/10.1117/12.2684047) - "Data downlink prioritization using image classification on-board a 6U CubeSat"
- **Technical Framework**: [Official Hackathon README](https://github.com/Hack4Dev/CubeSat_ImageClassify?tab=readme-ov-file) - Complete competition guidelines and notebook structure

### 🛰️ Core Problem Statement
Based on the original research work:
> **"Data downlink prioritization using image classification on-board a 6U CubeSat"**  
> *Keenan A. A. Chatar, Ezra Fielding, Kei Sano, and Kentaro Kitamura*  
> Proc. SPIE 12729, Sensors, Systems, and Next-Generation Satellites XXVII (2023)

**Challenge:** CubeSats face severe limitations in:
- 📡 **Data transmission bandwidth** (slow downlink speeds)
- 💾 **Onboard storage capacity**
- ⚡ **Computational resources**
- 🔋 **Power constraints**

## ⚡ Cloud Computing Infrastructure

### Ilifu Cloud Platform
During the hackathon, we utilized the **Ilifu Cloud Computing Infrastructure** for all model training and data analysis:

- **🖥️ High-performance computing** for deep learning training
- **💾 Large-scale data storage** for satellite imagery datasets
- **⚡ GPU acceleration** for faster model convergence
- **🔧 Pre-configured environments** with all necessary dependencies

The Ilifu platform provided the computational power needed to efficiently process, high-resolution satellite images and train multiple model architectures simultaneously.

## 📊 Dataset Information

### Original Dataset
- **Source:** [Zenodo CubeSat Dataset](https://zenodo.org/records/14598875)
- **Size:** 20,234 images total
- **Dimensions:** 3×512×512 (RGB channels, 512px resolution)
- **Format:** NumPy arrays (.npy files)

### Class Distribution
| Category | Training Samples | Test Samples | Description |
|----------|------------------|--------------|-------------|
| **Blurry** | 3,544 | 887 | Out-of-focus or motion-blurred images |
| **Corrupt** | 1,070 | 268 | Data transmission errors or file corruption |
| **Missing Data** | 2,021 | 506 | Incomplete image data packets |
| **Noisy** | 3,582 | 896 | High sensor noise or interference |
| **Priority** | 5968 | 1492 | High-quality images for scientific analysis |

    
