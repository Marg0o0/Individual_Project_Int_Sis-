# Emotion Detection with CNN + Fuzzy Logic

This project implements a Convolutional Neural Network (CNN) to classify **seven facial emotions** (angry, disgust, fear, happy, neutral, sad, surprise) from the FER2013 dataset.  

A **fuzzy layer** is added on top of the CNN to estimate **emotion intensity** (slightly, moderately, highly), providing a more interpretable measure of how strongly each emotion is expressed.  

Preprocessing includes grayscale conversion, resizing, normalization, and filtering of invalid/noisy images. The model uses stratified k-fold cross-validation, early stopping, and class-weighted loss to handle dataset imbalance.
