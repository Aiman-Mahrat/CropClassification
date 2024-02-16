# Crop Classification Using Modified ResNet34 Model

This repository contains a Jupyter notebook (CropClassification_ResNet.ipynb) that demonstrates the process of assessing crop damage using a modified ResNet34 model. The notebook guides through the steps of importing datasets, potentially applying image filters, upsampling to balance the dataset, defining image generators, testing the model on a test dataset, and finally creating a CSV file containing classifications.

## Overview

The notebook is structured as follows:

1. Crop Damage Assessment Using a Modified ResNet34 Model: An introduction to the project's objective and overview of the approach.
2. Image Filters (Optional): Discusses optional preprocessing steps to enhance image quality for better model performance.
3. Importing Dataset + Upsampling: Details the process of loading the dataset and applying upsampling techniques to balance the classes.
4. Modified ResNet34 Model: Describes the modifications made to the standard ResNet34 model to tailor it for crop damage assessment.
5. Defining Image Generators: Covers the creation of image generators for training and validation datasets.
6. Testing Model on a Test Dataset: Illustrates the process of evaluating the model's performance on a separate test dataset.

## Prerequisites
To run this notebook, you will need a Python environment with Jupyter Notebook or JupyterLab installed. Additionally, the following Python libraries are required:

TensorFlow (preferably with GPU support for faster training), Keras, NumPy, Pandas

## How to Use
Clone this repository to your local machine.
Ensure you have the required Python environment and libraries installed.
Open CropClassification_ResNet.ipynb in Jupyter Notebook or JupyterLab.
Follow the instructions within the notebook to execute the cells.
