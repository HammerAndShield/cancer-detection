# Cancer Detection Mini-Project

Mini-project for binary image classification using CNNs to detect metastatic cancer in histopathology images.

## Project Overview
- Problem: Binary classification of cancer in microscopic tissue images
- Dataset: Roughly 220k training images, and about 57k test images (96x96 pixels, RGB)
- Models: Baseline CNN, Improved CNN with BatchNorm/Dropout, Transfer Learning with ResNet50
- Best Result: 0.5226 AUC-ROC score on Kaggle test set

## Contents
- cancer_detection.ipynb: Main notebook with analysis and model code

## The Data
The data is too large to keep in the repository, but you can retrieve it from Kaggle:

https://www.kaggle.com/competitions/histopathologic-cancer-detection/submissions

## Requirements
- Python 3.x
- Keras
- NumPy
- Pandas
- Pillow (PIL)
- scikit-learn

## Usage
Run the Jupyter notebook `cancer_detection.ipynb` to see the analysis and model training process.
