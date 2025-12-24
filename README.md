# ResNet18 MNIST Training Comparison

This project demonstrates training and comparison of two ResNet18 models on the MNIST dataset.

## Description

Two models with identical ResNet18 architecture were trained:

- Model 1: Training without data augmentation
- Model 2: Training with data augmentation (random rotation)

Both models were trained for 5 epochs using the same optimizer and loss function.

## Dataset

- MNIST handwritten digits dataset
- Images resized to 224x224 and converted to 3 channels

## Model

- Architecture: ResNet18 (pretrained on ImageNet)
- Final fully connected layer modified for 10 classes

## Training

- Optimizer: Adam
- Loss Function: CrossEntropyLoss
- Epochs: 5

## Results

The training accuracy curves show that both models reach high accuracy.
Data augmentation slightly affects the training behavior and helps improve generalization.

## Accuracy Comparison

![Accuracy Plot](accuracy_plot.png)
