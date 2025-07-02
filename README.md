# JellyFish_Classification
Aim
The aim of this project is to design and implement a deep learning-based image classification model to accurately identify and classify different species of jellyfish from underwater images.
Problem Statement
Given a dataset of jellyfish images belonging to six categories:
Moon jellyfish
Barrel jellyfish
Blue jellyfish
Compass jellyfish
Lion’s mane jellyfish
Mauve stinger jellyfish

The goal is to develop a deep learning model that accurately classifies these images into their respective species. This helps automate jellyfish identification, supporting marine biodiversity monitoring and ecological research.

Models Implemented
1. Artificial Neural Network (ANN)
Input Layer: 1
Hidden Layers: 5
Dropout Layers: 2
Output Layer: 1

2. Convolutional Neural Network (CNN)
Input Layer: 1
Convolutional Layers: 4
Pooling Layers: 4 (MaxPooling2D after each Conv2D)
Dense (Fully Connected) Layers: 3
Dropout Layers: 2 (Dropout rate: 0.2)
Output Layer: 1

Model Performance
Model	Accuracy	  Loss
ANN	  ~55%	      1.28
CNN	  ~77%	      1.05

The CNN model significantly outperformed the ANN model. Its ability to extract spatial features from images contributed to its superior performance on this classification task. In contrast, the ANN model used flattened input data, which limited its effectiveness.

Conclusion
This project highlights the effectiveness of CNNs in image classification tasks, especially in domains like marine biology, where spatial image features are crucial. CNNs demonstrated a clear advantage over traditional ANN approaches for jellyfish classification from underwater images.
