# Custom ResNet Architecture for Image Classification

This project implements a custom ResNet architecture in PyTorch to classify a dataset containing 50 classes. The dataset consists of images sized at 64x64 pixels. It's unviersity project for neural
network course.

## Edit 
Model achived 73% accuracy on test set.

## Project Overview

### Problem Statement
- **Task**: Multi-class image classification.
- **Dataset**: Contains 50 distinct classes, with images sized at 64x64 pixels.

### Solution
- **Model Architecture**: A custom ResNet implementation, designed specifically for this classification problem.
- **Key Features**:
  - Residual blocks with skip connections for improved gradient flow.
  - Layer normalization to stabilize training.
  - Global average pooling to reduce model parameters and computational cost.
  - Efficient regularization techniques to prevent overfitting.

### Model Components
1. **Residual Blocks**:
   - Residual blocks(fully preactivated) with batch normalization and ReLU activation.
   - Skip connections to facilitate gradient flow.

### Training Details
- **Optimizer**: Adam with learning rate scheduling.
- **Loss Function**: Cross-entropy loss for multi-class classification.
- **Evaluation Metrics**:
  - Overall classification accuracy.
  - Loss value

### Implementation Highlights
- **Data Augmentation**:
  - Random cropping, flipping, and normalization.
  - Custom augmentation pipeline to increase data variability.


