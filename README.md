# Bachelor Thesis:  Optimizing Privacy and Efficiency in Brain Tumor Classification through Advanced Non-IID Federated Deep Learning
 
This repository hosts the code and resources for the thesis **"Federated Deep Learning for Brain Tumor Classification using MRI Data."** The research integrates advanced deep learning techniques and Federated Learning (FL) to tackle challenges in medical diagnostics, particularly brain tumor classification.

## Overview
The study enhances the MobileNetV3 architecture with:
- **Squeeze-and-Excitation (SE)** blocks.
- **Convolutional Block Attention Module (CBAM)** blocks.

A novel **non-IID data partitioning strategy** is introduced to address real-world data heterogeneity. The model utilizes the **Flower Framework** and is optimized with the **FedOpt algorithm**, ensuring efficient training while maintaining data privacy.

## Key Highlights
- **Objective**: Develop a scalable, privacy-preserving FL framework for brain tumor classification.
- **Model Architecture**: Enhanced MobileNetV3 with SE and CBAM blocks.
- **Performance**: Achieved **97.40% accuracy** in 8 training rounds.
- **Efficiency**: Operates effectively on **15GB RAM** and **10GB GPU memory**.
- **Data Handling**: Tackles non-IID data challenges with a custom partitioning strategy.
- **Framework**: Built using **Flower** for federated learning implementation.

## Significance
This research demonstrates the potential of Federated Learning in medical AI applications by addressing key challenges such as:
- Data privacy.
- Resource constraints.
- Heterogeneous data distribution.

The study contributes to secure and scalable AI solutions for medical diagnostics, paving the way for future advancements in healthcare technology.

## Repository Contents
- The implemented federated learning model.
- Training scripts and configurations.
- Instructions for reproducing the results.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Bachelor-thesis.git
