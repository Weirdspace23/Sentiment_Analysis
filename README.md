Image Classification Using CNN and Classical Machine Learning

A computer vision project that compares deep learning and traditional machine learning pipelines for image classification.

This project implements a Convolutional Neural Network (CNN) from scratch and compares it with classical approaches using HOG, LBP, PCA, and SVM.

Project Motivation

Modern computer vision heavily relies on deep learning, but classical feature-based pipelines still provide valuable insights into how images can be represented and classified.

This project explores:

How CNNs learn hierarchical image features

How handcrafted features like HOG and LBP perform in comparison

The impact of dimensionality reduction with PCA

Error analysis through misclassified samples

Project Pipeline
Deep Learning Approach

CNN implemented from scratch.

Pipeline:

Image → Convolution → Activation → Pooling → Fully Connected → Prediction

Key Components:

Convolution Layers

ReLU Activation

Pooling Layers

Fully Connected Layers

Model Training & Evaluation

Classical Machine Learning Pipeline

Feature-based classification using traditional methods.

Image → Feature Extraction (HOG / LBP) → PCA → SVM Classifier → Prediction

Techniques Used:

HOG (Histogram of Oriented Gradients)
Captures edge and gradient structures in images.

LBP (Local Binary Patterns)
Captures local texture patterns.

PCA (Principal Component Analysis)
Reduces feature dimensionality while preserving variance.

SVM (Support Vector Machine)
Performs classification using optimized hyperplanes.

Misclassification Analysis

The notebook includes visualization of incorrectly predicted images to:

Understand model weaknesses

Identify confusing patterns

Improve feature design

This step is critical for model debugging and improvement.

Technologies Used

Python ecosystem tools:

Python

NumPy

Scikit-learn

OpenCV

Scikit-image

Matplotlib

Jupyter Notebook
