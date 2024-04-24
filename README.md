# CNN Model Definitions for Binary Classification

## Overview
This repository contains TensorFlow's Keras API implementations for two Convolutional Neural Network (CNN) models designed for binary image classification tasks. The models are built using TensorFlow's Keras API and are intended to classify images into two categories. The models leverage convolutional layers for feature extraction followed by dense layers for classification.

## Models
1. **Model 1:** A simple CNN suitable for baseline comparisons.
2. **Model 2:** A more complex CNN designed to test deeper architectures and potentially achieve higher accuracy.

## Code Structure
- `build_model_1()`: Defines the architecture of Model 1.
- `build_model_2()`: Defines the architecture of Model 2.
- `Training the CNN models`: Code snippets to train both models.
- `Visualization of training and validation metrics`: Code to visualize training and validation metrics.
- `compute_auc(model, generator)`: Function to compute the Area Under Curve (AUC) for a given model.
- `Comparison of CNN and MLP Models Using ROC and AUC`: Analysis comparing the performance of CNN models with Multi-Layer Perceptron (MLP) models using ROC and AUC metrics.

## Usage
1. Ensure TensorFlow and other necessary dependencies are installed.
2. Run the provided code snippets to build, train, and evaluate the models.
3. Adjust hyperparameters, model architectures, or data preprocessing techniques as needed.

## Example Output
The provided output demonstrates the training process and evaluation results for both Model 1 and Model 2. Additionally, it includes the computation of AUC scores and a comparison analysis between the CNN and MLP models.

## Conclusion
The close AUC scores near random chance for both the CNN models indicate a need for further optimization and experimentation. Enhancements such as model tuning, data augmentation, or feature engineering might be necessary to improve discriminatory power and predictive performance.

