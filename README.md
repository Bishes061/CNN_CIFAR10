
# CIFAR-10 Image Classification

This project focuses on training a deep-learning model to classify images from the CIFAR-10 dataset. CIFAR-10 is a widely used dataset comprising 60,000 32x32 colour images in 10 classes, with 6,000 images per class. This repository demonstrates preprocessing, model training, evaluation, and visualization of results.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Results](#results)
- [License](#license)

---

## Introduction
This project aims to build and evaluate a deep learning model for image classification. It uses TensorFlow/Keras to train a convolutional neural network (CNN) on the CIFAR-10 dataset.

---

## Dataset
The CIFAR-10 dataset includes 10 classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

The dataset is split into:
- **Training Set**: 50,000 images
- **Test Set**: 10,000 images

---

## Project Structure
- **Data Loading & Preprocessing**: Loading CIFAR-10 data and normalizing images.
- **Model Architecture**: Defining a CNN with multiple convolutional and dense layers.
- **Training**: Compiling and training the model with a defined optimizer and loss function.
- **Evaluation**: Evaluating model accuracy on test data.
- **Visualization**: Plotting loss and accuracy metrics.

---

## Dependencies
To run this project, install the following dependencies:
- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib

Install dependencies using:
```bash
pip install tensorflow numpy matplotlib
```

---

## Results
- **Model Accuracy**: Achieved an accuracy of `74.2%` on the test set.
- **Visualizations**:
  - Training and validation loss over epochs.
  - Training and validation accuracy over epochs.

---
