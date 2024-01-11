# COVID-19 vs Viral Fever vs Normal Health Classification using Chest X-ray Images

This repository contains the code implementation for a COVID-19 image classification model. The goal of the project is to automate the process of reading X-rays to determine if a person is affected by COVID-19, has a viral fever, or is in normal health. 

# Dataset
The dataset used for training the model is sourced from Kaggle and can be found [here](https://www.kaggle.com/pranavraikokte/covid19-image-dataset).

# Methodology

The model was trained using the Keras library, utilizing the flow_from_directory method to efficiently feed data to the model. Global average pooling was employed instead of max pooling, and various model structures were tested to optimize performance. Additionally, a pre-trained model, ResNet50, was incorporated to benefit from its feature extraction capabilities.
