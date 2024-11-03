# Custom-Training-Loop-for-ResNet56x2-on-CIFAR10-using-TensorFlow-and-Keras

## Project Overview

Implementation of a custom training loop for ResNet56x2 on CIFAR10 dataset, utilizing data augmentation and manual handling of metrics and gradients, built using TensorFlow.

## Features

- Custom training loop from scratch
- ResNet56x2 architecture implementation
- CIFAR10 dataset loading and preprocessing
- Data augmentation:
    - Random cropping
    - Horizontal flipping
- Manual handling of:
    - Metrics (accuracy, loss)
    - Optimization (gradient calculation, learning rate scheduling)
- Low-level optimization control

## Implementation Details

- Framework: TensorFlow and Keras
- ResNet56x2 architecture with 2x 56-layer residual blocks
- Data augmentation using random crop and horizontal flip
- Manual metric calculation and gradient handling using TensorFlow ops
- Custom training loop with adjustable hyperparameters

## Requirements

- Python 3.x
- TensorFlow 2.x
- NumPy
- Matplotlib (for visualization)

## Usage

1. Clone repository
2. Install requirements
3. Run training script
4. Evaluate model performance on CIFAR10 test dataset

## Example Use Cases

- Training deep neural networks with custom architectures
- Experimenting with data augmentation techniques
- Understanding low-level details of training loops

## References

- He, Kaiming, X. Zhang, Shaoqing Ren and Jian Sun. “Deep Residual Learning for Image Recognition.” 2016 IEEE Conference on Computer Vision and Pattern Recognition (CVPR) (2015): 770-778.
