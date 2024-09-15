# Fine-Tuning Vision Transformer (ViT) on CIFAR-10 using PyTorch

This repository contains an implementation for fine-tuning a Vision Transformer (ViT) model from Hugging Face on the CIFAR-10 dataset using PyTorch. The Vision Transformer (ViT) is a state-of-the-art architecture initially designed for image classification tasks, which uses transformer-based models typically seen in natural language processing (NLP).

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Dataset](#dataset)
- [Model](#model)
- [Training](#training)
- [Evaluation](#evaluation)
- [Visualizing Predictions](#visualizing-predictions)
- [Results](#results)
- [Future Work](#future-work)
- [License](#license)

## Overview
This project fine-tunes a pre-trained ViT model from the Hugging Face `transformers` library for image classification on the CIFAR-10 dataset. The CIFAR-10 dataset contains 60,000 32x32 color images in 10 classes, with 6,000 images per class.

ViT applies the transformer architecture to image patches and is known for achieving competitive results on various image classification benchmarks.

## Features
- Fine-tuning of a pre-trained Vision Transformer model for CIFAR-10.
- Use of PyTorch for data loading, training, and evaluation.
- Pre-trained weights from Hugging Face's `transformers` library.
- Real-time performance monitoring with training and validation loss/accuracy.
- Image visualization and model prediction comparison.

## Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/varnit-mittal/SIH_Internal
cd SIH_Internal

# Install required Python packages
pip install torch torchvision transformers matplotlib
