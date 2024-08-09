# Breast-Cancer-Recognition-via-Neural-Networks-


## Overview

This project aims to build a breast cancer classifier using deep learning techniques. We will utilize a Convolutional Neural Network (CNN) to classify histology images as benign or malignant. This README provides an overview of the project, its objectives, and how to set it up and run it.

## What is Deep Learning?

Deep Learning is an advanced approach to Machine Learning inspired by the structure and function of the human brain. It involves neural networks with multiple layers that process data to extract complex patterns and features. Deep Learning techniques are widely used in various fields such as computer vision, speech recognition, natural language processing, and more.

## What is Keras?

Keras is an open-source neural-network library written in Python. It provides a high-level API for building and training deep learning models. Keras can run on top of several frameworks, including TensorFlow, CNTK, and Theano. It is designed for fast experimentation and prototyping, with a user-friendly and modular interface.

## Breast Cancer Classification – Objective

The objective of this project is to build a classifier that can accurately categorize breast cancer histology images as benign or malignant using the IDC dataset.

## Breast Cancer Classification – About the Python Project

In this project, we will:

1. **Data Preparation**: Train the classifier using 80% of the IDC breast cancer histology image dataset and reserve 10% of the data for validation.
2. **Model Development**: Define a CNN architecture named CancerNet using Keras and train it on the dataset.
3. **Performance Evaluation**: Analyze the model's performance by generating a confusion matrix.

**IDC** stands for Invasive Ductal Carcinoma, a common form of breast cancer that accounts for 80% of all breast cancer diagnoses. **Histology** is the study of the microscopic structure of tissues.

This is the image of graph

[Uploading Screenshot 2024-08-09 at 12.52.30 PM.png…]()

## The Dataset

We use the `IDC_regular` dataset from Kaggle, which contains 277,524 patches of size 50x50 extracted from 162 whole mount slide images of breast cancer specimens. Out of these, 198,738 patches are negative, and 78,786 patches are positive for IDC. You can download the dataset [here](https://www.kaggle.com/c/histopathologic-cancer-detection/data). Ensure you have at least 3.02GB of disk space to download and store the dataset.

The filenames in the dataset are formatted as follows:

`8863_idx5_x451_y1451_class0`

- `8863_idx5` is the patient ID.
- `451` and `1451` are the x- and y-coordinates of the crop.
- `0` denotes the class label (0 for absence of IDC).

## Prerequisites

To run this project, you need to install the following Python packages:

- TensorFlow
- Keras
- NumPy
- Matplotlib
- scikit-learn

You can install these packages using pip:

```bash
pip install tensorflow keras numpy matplotlib scikit-learn



