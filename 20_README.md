# Potato Disease Classification with Deep Learning

## Problem Statement

The goal of this project is to automate the detection of diseases in potatoes using images of potato leaves. Accurate and timely disease detection is crucial for maintaining crop health and ensuring agricultural productivity. We aim to classify potato leaf images into categories indicative of health status or specific diseases.

## Explanation

This project explores the application of deep learning in classifying potato diseases using four different convolutional neural network (CNN) architectures:

1. **VGG16 without Fine-Tuning:** Utilizes the VGG16 model pre-trained on ImageNet as a fixed feature extractor, where only the classifier layers are trained on the potato disease dataset.

2. **VGG16 with Fine-Tuning:** Employs the VGG16 model with selective fine-tuning of layers to better adapt the pre-trained features for the specific task of potato disease classification.

3. **ResNet50:** Applies the ResNet50 architecture, leveraging its residual connections to efficiently train on the dataset for the task at hand.

4. **EfficientNet B1:** Implements EfficientNet B1, focusing on scaling model dimensions to balance network depth, width, and resolution, optimizing for accuracy and efficiency.

Each model is evaluated based on its ability to accurately classify the images into the correct disease categories.

## Dataset Link

The dataset used for this project can be found here: [Potato Disease Dataset]('https://www.kaggle.com/datasets/emmarex/plantdisease')

