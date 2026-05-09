# Fashion-MNIST-Classification-with-TensorFlow
This project implements a neural network using TensorFlow and Keras to classify images from the Fashion MNIST dataset. The notebook demonstrates the full workflow from data loading and preprocessing to model training and evaluation.

Features
Data Loading: Automatically fetches the Fashion MNIST dataset containing 70,000 grayscale images in 10 categories.
Preprocessing: Normalizes pixel values to a range of 0 to 1 for faster model convergence.
Neural Network Architecture:
  Input Layer: Flattens $28 \times 28$ pixel images.
  Hidden Layers: Two dense layers with 128 and 64 neurons using ReLU activation.
  Output Layer: Dense layer with 10 neurons and Softmax activation for multi-class classification.
Training: Optimized using the Adam optimizer and Sparse Categorical Crossentropy loss function.

DatasetThe Fashion MNIST dataset consists of:
  Training Set: 60,000 images.
  Test Set: 10,000 images.
  Resolution: $28 \times 28$ pixels.

Results
During training, the model achieves:

Training Accuracy: ~87% by epoch 3.

Validation Accuracy: ~87%.
