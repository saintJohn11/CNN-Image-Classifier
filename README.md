# CIFAR-10 Image Classifier 🖼️

A Convolutional Neural Network (CNN) built from scratch using PyTorch to classify images into 10 categories.

## Results
- Training Accuracy: 76%
- Test Accuracy: 77%

## Dataset
CIFAR-10 — 60,000 images across 10 classes:
`plane, car, bird, cat, deer, dog, frog, horse, ship, truck`

## Model Architecture
- 3 Convolutional layers with ReLU activation
- MaxPooling after each conv layer
- 2 Fully connected layers
- Dropout (0.5) for regularization

## Technologies
- Python
- PyTorch
- Torchvision
- Matplotlib

## How to Run
1. Open the notebook in Google Colab
2. Enable GPU (Runtime → Change runtime type → T4 GPU)
3. Run all cells

## What I Learned
- Building CNNs from scratch in PyTorch
- Image preprocessing and data augmentation
- Training loops, backpropagation, and optimization
- Model evaluation and visualization
