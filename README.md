# Handwritten Digit Recognition: Deep Neural Network (Keras / TensorFlow)

> I trained a deep neural network on MNIST to read handwriting from people it had never seen.

🔒 The code sits in a private repository because this was King's College London coursework. Ask me and I'll walk you through it.

## Overview
The network classifies 28×28 greyscale digits. My marker tested it on a hidden set of about 12,000 digits from new writers, so I had to stop it overfitting to the MNIST training data.

## What I built
- **Network design:** a Keras/TensorFlow 2.18 model that hits high accuracy inside a strict model-size limit
- **Data pipeline:** a loader that normalises the images and reshapes them for MLP or CNN input
- **Training:** mini-batch training with cross-entropy loss, a validation split, and accuracy/loss plots I used to spot under- and overfitting
- **Error analysis:** an evaluation script that plots each misclassified digit beside the model's class probabilities
- **Robustness check:** I ran the model on Fashion-MNIST-style data to see how it copes with a shift in distribution

## Skills
Deep learning · network design · regularisation · model evaluation · Python

## Tech stack
Python · TensorFlow 2.18 · Keras · NumPy · Matplotlib
