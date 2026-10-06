# Galaxy Morphology Classification: CNN vs Vision Transformer

A deep learning project for classifying galaxy images based on their morphological characteristics using two different computer vision architectures: a Convolutional Neural Network (CNN) and a Vision Transformer (ViT).

## 📌 Project Overview

Galaxy morphology classification is an important task in astronomical image analysis, where galaxies are categorized based on their visual structures and shapes.

In this project, two deep learning approaches are developed and evaluated on the same galaxy classification task:

- **Convolutional Neural Network (CNN)** — A traditional image classification architecture that learns spatial features through convolutional layers.
- **Vision Transformer (ViT)** — A transformer-based architecture that processes image patches and learns relationships between different regions of an image.

The objective is to compare their classification performance and determine which architecture performs better for galaxy morphology classification.

## 🎯 Objectives

- Develop a CNN-based galaxy morphology classifier.
- Develop a Vision Transformer-based galaxy morphology classifier.
- Train and evaluate both models on the same classification task.
- Compare their performance using accuracy and F1-score.
- Analyze the models using training curves and confusion matrices.
- Study prediction confidence and classification behavior.
- Determine which architecture provides better overall performance.

## 🧠 Models Used

### 1. Convolutional Neural Network (CNN)

The CNN learns hierarchical visual features from galaxy images using convolutional operations and progressively extracts spatial patterns useful for classification.

### 2. Vision Transformer (ViT)

The Vision Transformer divides images into patches and uses transformer encoder blocks to learn relationships between different image regions before performing classification.

## 📊 Performance Comparison

| Metric | CNN | Vision Transformer |
|---|---:|---:|
| Best Validation Accuracy | 46.13% | **64.59%** |
| Test Accuracy | 44.80% | **62.68%** |
| Macro F1-Score | 42.22% | **59.64%** |
| Weighted F1-Score | 43.49% | **62.33%** |
| Parameters | 422,602 | 545,546 |

## 🔍 Key Findings

- The CNN achieved a test accuracy of **44.80%**.
- The Vision Transformer achieved a higher test accuracy of **62.68%**.
- The ViT improved test accuracy by **17.88 percentage points** compared with the CNN.
- The ViT also achieved higher Macro F1 and Weighted F1 scores.
- The ViT achieved a best validation accuracy of **64.59%**, compared with **46.13%** for the CNN.
- The ViT uses more parameters than the CNN, but achieved substantially better classification performance in this experiment.

## 📈 Results and Analysis

The project includes visual analysis of both models through:

- Training and validation accuracy curves
- Training and validation loss curves
- CNN confusion matrix
- Vision Transformer confusion matrix
- CNN vs ViT performance comparison
- ViT prediction confidence analysis

All major result figures are available in the [`results`](./Results) directory.

## 📁 Repository Structure

```text
Galaxy_Morphology_Classification/
│
├── CNN/
│   └── CNN notebook
│
├── Vision_Transformer/
│   └── ViT notebook
│
├── results/
│   ├── cnn_training_history.png
│   ├── vit_training_history.png
│   ├── cnn_confusion_matrix.png
│   ├── vit_confusion_matrix.png
│   ├── cnn_vs_vit_comparison.png
│   └── vit_prediction_confidence.png
│
├── Comparison/
│   └── README.md
│
├── README.md
└── .gitignore
