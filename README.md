# Handwritten Digit Recognition – Deep Neural Network (Keras / TensorFlow)

> A deep neural network trained on MNIST that is built to generalise to handwriting it has never seen.

🔒 **The source code is in a private repository** because this was university coursework at King's College London. I'm happy to walk through the code on request.

## Overview
I designed and trained a deep neural network to classify 28×28 greyscale handwritten digits. It was not marked on the standard MNIST test set. It was marked on a hidden set of about 12,000 digits written by different people, so avoiding overfitting was the main challenge.

## What I built
- **Network design:** a Keras/TensorFlow 2.18 network built to hit high accuracy while keeping the parameter count within a strict model-size limit
- **Data pipeline:** a reusable loader that normalises inputs and reshapes them for either MLP or CNN architectures
- **Training and monitoring:** mini-batch training with cross-entropy loss, validation monitoring, and plotted accuracy/loss curves to diagnose under- or overfitting
- **Error analysis:** an extended evaluation script that plots misclassified digits alongside the model's predicted class probabilities
- **Robustness testing:** the model was also evaluated on Fashion-MNIST-style data to see how it behaves under distribution shift

## Skills demonstrated
Deep learning · network architecture design · regularisation and generalisation · model evaluation · Python data tooling

## Tech stack
Python · TensorFlow 2.18 · Keras · NumPy · Matplotlib
