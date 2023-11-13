# Project Title: American Sign Language (ASL) Image Classification
Deep learning: Image Classification using a Convolutional Neural Network

## Overview
American Sign Language (ASL) serves as a primary means of communication for many deaf individuals. This project delves into the development of a convolutional neural network (CNN) designed to classify images of ASL letters. The primary goal is to construct a model capable of recognizing individual letters, laying the groundwork for the creation of a sign language translation system.

## Project Structure

### 1. Introduction to ASL
- Brief overview of American Sign Language and its significance.
- Discussion on the relevance of computer vision systems in translating sign language to spoken language.

### 2. Data Loading and Preprocessing
- Utilization of a pre-shuffled dataset containing images of ASL letters.
- Loading, examining, and preprocessing the data for model training.

### 3. Visualizing the Training Data
- Displaying a selection of training images along with their corresponding labels (letters).

### 4. Dataset Examination
- Analyzing the distribution of letters in the training and test datasets to ensure balance.

### 5. One-Hot Encoding
- Transforming categorical labels into one-hot encoded vectors for model training.

### 6. Model Definition
- Building a CNN to classify ASL images with convolutional and pooling layers.
- Model summary to provide an overview of the network architecture.

### 7. Model Compilation
- Compiling the model with an appropriate loss function, optimizer, and evaluation metric.

### 8. Model Training
- Fitting the model to the training data and evaluating its performance on the validation set.

### 9. Model Testing
- Evaluating the trained model on the test dataset to assess its accuracy.

### 10. Visualizing Misclassifications
- Identifying and displaying images that were misclassified by the model for further analysis.

## How to Use
1. Ensure you have the necessary dependencies installed (e.g., TensorFlow, NumPy, Matplotlib).
2. Execute the provided code cells in a Jupyter notebook or an equivalent environment.
3. Follow the step-by-step instructions for data loading, preprocessing, model training, and evaluation.
4. Examine the model's performance on the test set and visualize misclassifications.

## Conclusion
The CNN model for ASL image classification gives an accuracy of 93% on the test set. Further enhancements and refinements can be explored to improve the model's accuracy and robustness using Dropuouts or Batch Normalization including considering more epochs during the training process.
