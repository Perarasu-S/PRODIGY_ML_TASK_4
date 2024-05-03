# PRODIGY_ML_04
ML Internship at [Prodigy InfoTech](https://prodigyinfotech.dev) 

Task - 04

# Hand-Gesture recognition model

This repository contains code on Developing a hand gesture recognition model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.

## Algorithm:

1. **Data Preprocessing:**
   - Split the dataset into training and validation sets.

2. **Model Definition:**
   - Create a Convolutional Neural Network (CNN) model using TensorFlow and Keras.
  
4. **Data Augmentation:**
   - Apply data augmentation techniques using the `ImageDataGenerator` to create variations in the training set.

5. **Model Compilation:**
   - Compile the model with an appropriate optimizer (e.g., Adam), categorical crossentropy loss, and accuracy as the metric.

6. **Model Training:**
   - Train the model using the augmented training set.
   - Specify the number of epochs and monitor the validation accuracy.

7. **Model Evaluation:**
   - Evaluate the model on the validation set to assess its performance.
   - Display the accuracy achieved on the validation set.

8. **Confusion Matrix:**
   - Use scikit-learn's `confusion_matrix` to compute the confusion matrix based on the model's predictions on the validation set.

## Usage:
1) Dataset from Kaggle [Hand Gesture](https://www.kaggle.com/gti-upm/leapgestrecog).
2) Used Jupiter Notebook for Python Coding.

## Techniques:
The following techniques are implemented in this project:
- CNN model
