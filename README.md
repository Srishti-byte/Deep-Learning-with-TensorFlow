# Deep Learning with TensorFlow

A collection of deep learning projects implemented using **TensorFlow** and **Keras** as part of my learning journey.

## Project: MNIST Handwritten Digit Classification (MLP)

### Objective
Build and train a Multi-Layer Perceptron (MLP) to classify handwritten digits from the MNIST dataset.

### Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

### Workflow
- Load and preprocess the MNIST dataset
- Normalize pixel values
- Build an MLP using the Keras Sequential API
- Train and evaluate the model
- Visualize accuracy and loss
- Generate predictions on test images

### Model Architecture

```text
Input (28×28)
      ↓
Flatten
      ↓
Dense (128, ReLU)
      ↓
Dense (10, Softmax)
```

### Results
- Test Accuracy: **97.72%**
- Test Loss: **0.0844**

## Repository Structure

```text
├── MNIST_MLP_TensorFlow.ipynb
├── README.md
└── LICENSE
```

---
*More TensorFlow and deep learning projects will be added as I continue learning.*
