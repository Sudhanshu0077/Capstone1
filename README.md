For-rest from Fires: Fire Detection Model Using Deep Learning
Project Overview

This project focuses on creating a fire detection system using deep learning to identify fire and non-fire images from surveillance camera data. The model leverages a Convolutional Neural Network (CNN) to classify fire and non-fire imagery, aiming for high accuracy and efficient performance.
Requirements
Prerequisites

To run this project, ensure that the following are installed on your machine:
    Python 3.8+
    pip (Python package manager)
    The dataset is stored in the directory:

Dataset
The dataset is stored in the directory
Ensure the dataset is properly structured, with subfolders for fire and non_fire images.

Model Pipeline

The pipeline consists of several stages, including data preprocessing, model training, and performance evaluation. Follow the steps below to execute the pipeline.
1. Data Preprocessing
The data preprocessing script prepares the images for training by resizing, normalizing, and splitting the dataset into training, validation, and test sets.
This will:

    Resize the images to a suitable input size for the CNN.
    Normalize pixel values to improve model performance.
    Split the dataset into training, validation, and test sets (default split: 80/10/10).

2. Training the Model
Once the data is preprocessed, you can train the fire detection model using the CNN architecture. 

Hyperparameter Tuning 
For model optimization, you can use hyperparameter tuning to find the best model configuration, such as learning rate, batch size, and the number of convolutional layers.

Evaluate Model Performance

After training the model, evaluate its performance on the test set using accuracy, precision, recall, and F1 score.

This will output:

    Accuracy: The overall classification accuracy of the model on the test data.
    Confusion Matrix: A visual representation of true positives, false positives, true negatives, and false negatives.
    Precision and Recall: Measures for understanding how well the model performs in terms of minimizing false positives and false negatives.
    F1 Score: A balanced metric to evaluate model performance.

    Performance Metrics

The target accuracy for this model is >85% on the test dataset. The performance evaluation script will display the model's accuracy, confusion matrix, precision, recall, and F1 score.

