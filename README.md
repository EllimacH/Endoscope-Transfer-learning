# Endoscope-Transfer-learning

This project focuses on transfer learning using ResNet50 and DINOv1 for endoscopic image analysis. The goal is to leverage pre-trained models to improve the accuracy and efficiency of disease detection and image quality assessment in endoscopic procedures.

## Introduction

Endoscopic procedures generate a large number of images that need to be analyzed for disease detection and quality assessment. This project uses transfer learning techniques to fine-tune a ResNet50 model pre-trained with DINOv1 on a custom dataset of endoscopic images.

## Project Structure

- `disease_detection.ipynb`: Jupyter notebook for disease detection using transfer learning.
- `Transfer_learning.ipynb`: Jupyter notebook for transfer learning and model training for image quality.
- `Location_model_1.pth`: Pre-trained model for location-based analysis.
- `quality_model_500_2.pth`: Pre-trained model for image quality assessment.

## Usage

1. Open the Jupyter notebooks (`disease_detection.ipynb` and `Transfer_learning.ipynb`) to explore the code and run the experiments.
2. Follow the instructions in the notebooks to train the models and evaluate their performance.

## Models

- **ResNet50**: A deep residual network used for image classification tasks.
- **DINOv1**: A self-supervised learning method used to pre-train the ResNet50 model.

## Results

The project aims to achieve high accuracy in disease detection and image quality assessment through transfer learning. The results and performance metrics are documented within the Jupyter notebooks.

