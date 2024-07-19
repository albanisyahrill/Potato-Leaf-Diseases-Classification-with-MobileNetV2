# Potato Leaf Diseases Classification using MobileNetV2

## Overview
This project focuses on the classification of potato leaf diseases using the MobileNetV2 architecture. The goal is to accurately identify different types of diseases affecting potato leaves, which can help in timely and effective treatment, ultimately leading to improved crop yield and quality.

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Model Architecture](#model-architecture)
4. [Installation](#installation)

## Introduction
Potato plants are susceptible to various diseases that can significantly impact their yield and quality. Early detection and accurate classification of these diseases are crucial for effective management and treatment. This project leverages the MobileNetV2 architecture, known for its efficiency and accuracy, to classify different types of potato leaf diseases.

## Dataset
The dataset used in this project consists of images of potato leaves with different diseases. The images are categorized into the following classes:
1. Early Blight
2. Healthy
3. Late Blight

The dataset can be downloaded from [Kaggle Potato Leaf Dataset](https://www.kaggle.com/datasets/rizwan123456789/potato-disease-leaf-datasetpld).

## Model Architecture
MobileNetV2 is a convolutional neural network architecture that is optimized for mobile and embedded vision applications. It provides a good balance between accuracy and efficiency, making it suitable for real-time applications.

The architecture includes:
- Depthwise separable convolutions to reduce the number of parameters and computation.
- Linear bottleneck layers to improve efficiency.

## Installation
To run this project, you need to have Python installed along with the necessary libraries. Follow these steps to set up the environment:

1. Clone the repository:
    ```bash
    git clone https://github.com/albanisyahrill/Potato-Leaf-Diseases-Classification-with-MobileNetV2.git
    ```
