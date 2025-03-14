# Deconvolve

**Description:**  
[This project focuses on analyzing the CIFAR-10 dataset using a pre-trained CNN model. It includes functionality for generating Grad-CAM heatmaps to visualize feature activations and explain model predictions.]

---

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contact](#contact)

---

## Introduction

Convolutional Neural Networks (CNNs) have demonstrated exceptional accuracy in image classification and are widely used across various industries. However, understanding their decision-making process remains a challenge due to their black-box nature. To enhance model interpretability, we introduce DeConvolve—a post-hoc explainability methodology that leverages multimodal Large Language Models (LLMs) to extract human-understandable insights from CNN feature maps.

---

## Features

- **CIFAR-10 Dataset Filtering:** Filter the dataset to include specific classes (e.g., airplane, automobile, bird).
- **Model Prediction:** Use a pre-trained CNN model to classify images.
- **Grad-CAM Heatmaps:** Generate heatmaps to visualize feature activations.
- **Neuron Influence Analysis:** Analyze the influence of neurons on predictions.
- **Explainability:** Generate human-readable explanations for model predictions.

---

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/hrishikeshkh/XCNN.git
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```
---

## File Structure

```
[Project Root Directory]
│
├── assets/                   # Directory for heatmaps and images
├────[Heuristic.ipynb]        # Heuristic code
├────[pneumonia.ipynb]        # Preprocessing
├── [copy_of_cifar.py]        # Main script for CIFAR-10 analysis
├── [requirements.txt]        # Dependencies
├── [README.md]               # Project documentation
└── [Other files...]
```

---

## Contact

For any questions or feedback, please contact:


Repository Owner

---
