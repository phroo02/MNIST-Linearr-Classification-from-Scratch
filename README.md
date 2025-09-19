# MNIST: Linear Classification (3 vs 7)

This project implements a step-by-step mini-classifier using the MNIST dataset (restricted to digits 3 and 7). Starting from scratch, we:

- Load and preprocess image data (as raw pixel tensors)
- Implement a non-learned baseline (distance-to-mean classifier)
- Build and train a logistic regression model using PyTorch
- Train the model using manually written SGD
- Compare performance of the trained model to the baseline

### Why this matters

- Demonstrates understanding of low-level training logic (no high-level APIs)
- Shows knowledge of tensor operations, model training, gradients, and optimization
- Builds foundation for more complex models (e.g., neural networks)

### Tools used
- Python, PyTorch
- FastAI (for dataset access only)
