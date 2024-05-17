# CNN-Fruit-Classification-VGG16

## Introduction
This repository contains the completed tasks for a fruit classification using a Convolutional Neural Network (CNN) project based on VGG-16 architecture. The project was completed as part of a deep learning course, and each task focuses on different aspects of neural network implementation and optimization.

## Task: Fruit Classification (CNN)

### Project Description
This project involves creating a multiclass image classification application to identify different types of fruits using a CNN. The dataset used for this task is `Dataset2B`, consisting of images of four fruit classes.

### Steps and Solutions

1. **Data Exploration and Preprocessing**
   - **Histogram Analysis**: We analyzed the color histograms of the images to understand their distributions.
   - **Image Resizing**: Resized all images to 224x224 resolution.
   - **Data Splitting**: Divided the dataset into 80% training, 10% validation, and 10% test sets.

2. **Baseline CNN Architecture**
   - I implemented a VGG-16 based architecture with ReLU activation functions. We used a pre-trained VGG-16 model and applied fine-tuning techniques to adapt it to our specific dataset.

3. **Model Optimization**
   - Enhanced the architecture by incorporating dropout layers, batch normalization, and hyperparameter tuning to improve classification accuracy. Changes were made to address identified challenges in image quality and variability, enhancing the model’s generalization capability.

4. **Performance Evaluation**
   - The models were evaluated using the test set, reporting accuracy, precision, recall, and F1-Score. Detailed explanations of the results and the effectiveness of modifications were provided.
