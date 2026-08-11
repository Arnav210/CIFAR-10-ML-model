# CIFAR-10 Deep Learning Image Classifier

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1r1cvPoLcv_QC3phdKG9dWWvN62bzjCdE)

An interactive Google Colab notebook demonstrating deep learning computer vision techniques for multi-class image classification on the benchmark CIFAR-10 dataset.

## Performance & Model Results
* **Test Accuracy:** Achieved an **87% test classification accuracy** across 10 distinct image categories through iterative CNN architecture optimization.
* **Dataset Scope:** Evaluated on 60,000 32x32 color images across 10 classes (airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks).

## ML Pipeline & Model Architecture
* **Data Preprocessing & Augmentation:** Implemented normalization, random cropping, and horizontal flips to expand training set diversity and reduce generalization error.
* **Convolutional Neural Network (CNN):** Designed a multi-layer CNN architecture leveraging feature extraction layers, ReLU activations, and max-pooling operations.
* **Optimization & Regularization:** Incorporated **Dropout layers** and weight decay to prevent overfitting, alongside iterative learning rate adjustments during model training.
* **Evaluation & Metrics:** Visualized training/validation loss curves and classification performance over training epochs using Matplotlib.

## Tech Stack & Environment
* **Language:** Python 3
* **Frameworks & Libraries:** PyTorch / TensorFlow, NumPy, Matplotlib
* **Execution Environment:** Google Colab (GPU Accelerated)
