# Obesity Risk Prediction CNN Model

This repository hosts a Convolutional Neural Network (CNN) model that predicts the risk of obesity in individuals with an impressive accuracy of 87.01%. Developed on Google Colab, this model harnesses the platform's powerful GPUs and collaborative environment.

## Model Overview

- *Objective*: Accurately predict obesity risk from input data.
- *Accuracy*: Attained 87.01% on the test dataset.
- *Dataset*: Sourced from a Kaggle competition via its API.
- *Frameworks*: Built with TensorFlow/Keras.
- *Training Environment*: Google Colab.

## Features

- *Input*: Accepts data with shape (22, 1), including normalization and dropout layers.
- *Output*: Outputs the probability of obesity risk.
- *Architecture*: Consists of 5 layers, featuring convolutional layers, dropout layers, batch normalization, and fully connected layers.
- *Optimization*: Utilizes the Adam optimizer with a learning rate of 0.00005.

## Results

In a sample test of 10, the model correctly predicted 8 instances, indicating potential areas for improvement to enhance accuracy.

---

Your contributions and feedback are invaluable as we continue to refine this model. Feel free to clone and explore its capabilities!
