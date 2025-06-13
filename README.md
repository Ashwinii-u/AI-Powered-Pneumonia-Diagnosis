##  AI-Powered-Pneumonia-Diagnosis
# Objective
To develop a Convolutional Neural Network (CNN) model that detects pneumonia from chest X-ray images and deploy it using Streamlit for real-time predictions.

# Dataset Source
The dataset used for this project is from the Chest X-Ray Images (Pneumonia) dataset on Kaggle. It contains chest X-ray images categorized as 'Pneumonia' and 'Normal'.

# Tools and Libraries Used
Python
TensorFlow & Keras
Matplotlib & Seaborn (for visualization)
Streamlit (for web deployment)
NumPy, Pandas
PIL (for image processing)

# Project Workflow
Data Preprocessing
Image resizing
Data augmentation
Splitting data into training, validation, and test sets
Model Building
CNN architecture with multiple Conv2D, MaxPooling, and Dense layers
Model trained on training data and validated
Evaluation
Accuracy, loss plots
Confusion matrix
Classification report
Deployment
Model saved in .h5 format
Deployed using Streamlit with image upload feature for real-time inference

# Results
The CNN model achieved a high validation accuracy in detecting pneumonia from X-rays.
Deployed model allows users to upload chest X-ray images and instantly receive predictions.
