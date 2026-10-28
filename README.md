# Breast Cancer Classification: Perceptron vs ANN

Classifies breast tumors as **benign** or **malignant** from 30 cell-nucleus
measurements, and compares a single-neuron **Perceptron** with a small
**ANN** built in TensorFlow/Keras.

## Theory
- **Perceptron:** the simplest neural model, one neuron that draws a single
  straight decision boundary. It works well when the classes are close to
  linearly separable and serves as a fast baseline.
- **ANN:** adds a hidden layer. The **ReLU** activation lets it learn
  non-linear boundaries.
- **Sigmoid output:** squashes the output into a probability between 0 and 1.
  A value above 0.5 means class 1 (benign), otherwise class 0 (malignant).
- **Binary crossentropy:** the loss that matches a sigmoid output. It
  penalizes confident
