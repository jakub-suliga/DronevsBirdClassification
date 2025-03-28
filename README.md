# Drone vs Bird Classification

This is a small educational project designed to understand the fundamentals of CNNs and image classification.

## ToDo

1. Add ResNet Modell
2. Add Data Augmentation

## Model Architecture

The project includes a simple CNN architecture with:

- 3 convolutional layers with batch normalization
- Max pooling layers
- Dropout for regularization
- 2 fully connected layers
- Sigmoid activation for binary classification

## Dataset

The project uses the "Drone vs Bird" dataset from Kaggle, which contains images of birds and drones from various angles and environments.

## Installation

1. Clone this repository
2. Install the required packages:

``` python
pip install torch torchvision matplotlib scikit-learn kagglehub pillow
```

## License

This project is created for educational purposes.
