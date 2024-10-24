# QIANets: Quantum-Integrated Adaptive Networks for Reduced Latency and Improved Inference Times in CNN Models

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Research Contributions](#research-contributions)
4. [Technologies and Algorithms](#technologies-and-algorithms)
5. [Performance Metrics](#performance-metrics)
6. [Setup and Installation](#setup-and-installation)
7. [Usage](#usage)
8. [Contributing](#contributing)
9. [Contact Information](#contact-information)

---

## Introduction
**QIANets** is a quantum-inspired approach designed to reduce latency and improve inference times in **Convolutional Neural Networks (CNNs)**. By integrating **quantum-adaptive networks** with traditional CNN models like **ResNet-18**, **GoogLeNet**, and **DenseNet**, QIANets achieves significant model compression without sacrificing accuracy. This novel approach uses quantum-inspired techniques such as **pruning**, **tensor decomposition**, and **annealing efficient solution for real-world AI systems.

## Project Overview
- **Objective**: Optimize traditional CNNs by applying quantum-inspired techniques to reduce computational overhead, improve inference times, and minimize model size.
- **Key Focus**:
  - Quantum-inspired methods for CNN model enhancement.
  - Model compression techniques for practical AI deployments.
  - Performance comparisons between QIANets-enhanced CNNs and baseline models.

## Research Contributions
This project introduces and tests quantum-integrated methods in popular CNN architectures:
- **GoogLeNet**, **DenseNet**, and **ResNet-18**: Enhanced using quantum-inspired pruning and matrix factorization techniques.
- **Latency Reduction**: Demonstrates significant improvement in model inference time, enabling real-time applications.
- **Model Compression**: Reduces model size by over 50%, while retaining over 90% of the original accuracy.

Published Paper:
- [QIANets: Quantum-Integrated Adaptive Networks](https://arxiv.org/pdf/2410.10318v1)

## Technologies and Algorithms
- **Quantum-Inspired Algorithms**:
  - **Pruning**: Reduces model size by removing unnecessary parameters while maintaining model performance.
  - **Tensor Decomposition**: Decomposes large tensors into lower-dimensional forms for faster computation.
  - **Annealing-Based Matrix Factorization**: Inspired by quantum annealing, this technique optimizes weight matrices for reduced latency and enhanced efficiency.
  
- **CNN Architectures**: This project is applied to architectures such as **GoogLeNet**, **DenseNet**, and **ResNet-18**.

## Performance Metrics
- **Model Size Reduction**: Achieves over 50% size reduction in CNN models.
- **Accuracy Retention**: Maintains over 90% accuracy compared to the original models.
- **Inference Time**: Reduces latency by 30% to 50%, enabling faster predictions.
- **Benchmarks**: Comparative results for standard and QIANets-enhanced models across datasets like **CIFAR-10** and **ImageNet**.

## Setup and Installation

### Prerequisites
- Python 3.8+
- TensorFlow / PyTorch
- Quantum libraries (optional but recommended)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/EdwardMagongo/QIANets.git
   cd QIANets
