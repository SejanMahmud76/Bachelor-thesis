# Bachelor Thesis:  Optimizing Privacy and Efficiency in Brain Tumor Classification Through Advanced Non-IID Federated Deep Learning
 
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

## Conference Presentation
The paper, titled **“Optimizing Privacy and Efficiency in Brain Tumor Classification through Advanced Non-IID Federated Deep Learning”**, authored by **Md Samsuzzaman, R. H. Sezan, A. Golder, M. A. Masud, and G. M. M. Bashir**, has been:
- **Accepted and Presented** at the **2024 2nd International Conference on Information and Communication Technology (ICICT)**, held in Dhaka, Bangladesh, on October 21–22, 2024.  
- The paper is not yet published.  

For more details about the conference, visit the [ICICT official website](https://icict.buet.ac.bd/).

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
