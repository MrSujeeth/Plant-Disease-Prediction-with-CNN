**Plant-Disease-Prediction-with-CNN**

This project is a Convolutional Neural Network (CNN) based application for predicting plant diseases from leaf images. The model is trained using the PlantVillage dataset and can classify images into healthy or diseased categories.

Requirements

Python 3

TensorFlow

NumPy

Matplotlib

Pillow

Kaggle API

Dataset

The PlantVillage dataset is used in this project. It contains images of plant leaves in three formats:

Color

Grayscale

Segmented

Only the color images are used for training and testing.

Steps Performed

Import required libraries

Set random seeds for reproducibility

Download dataset using Kaggle API

Extract and explore dataset

Preprocess images and normalize pixel values

Create training and validation datasets

Build CNN model

Train the model

Evaluate model performance

Predict disease from a new image

Save trained model and class labels

Model Evaluation

The model is evaluated using validation accuracy and loss. Training and validation graphs are plotted to visualize performance.

Prediction

The trained model can predict the disease class of a given plant leaf image by preprocessing the image and passing it to the model.
