# AIXHW3

# Assignment 3: Explaining Black-Box Model Predictions using LIME

This repository contains my implementation of Assignment 3 for our AIX class, where I explore model interpretability using LIME (Local Interpretable Model-agnostic Explanations) with ResNet34.

## Project Overview
In this project, I:
- Use a pre-trained ResNet34 model for image classification
- Implement LIME to explain the model's predictions
- Visualize which parts of an image influence the model's decision
- Analyze the effectiveness and limitations of this approach

## Getting Started
To run this notebook:
1. Open the notebook in Google Colab
2. Run all cells in order
3. Download the golden retriever image from my github and use it in your notebook

## Requirements
The notebook uses these main libraries:
- torch
- torchvision
- lime
- PIL
- matplotlib
- numpy

All libraries can be installed using pip within the notebook.

## Implementation Details
The notebook includes:
- Model setup and initialization
- Image preprocessing
- LIME implementation
- Visualization of results
- Analysis of model predictions
- Discussion of limitations and possible improvements

## Results
The implementation successfully demonstrates how LIME can help us understand ResNet34's decision-making process, showing which parts of an image are most important for classification.
