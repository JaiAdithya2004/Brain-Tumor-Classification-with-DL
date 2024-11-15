🧠 Brain-Tumor-Classification-with-DL

Brain Tumor Classification using Deep Learning
This repository contains code for a deep learning model that classifies brain tumor images. The model is built using TensorFlow and Keras, with VGG19 as the backbone architecture. This project involves steps from data preprocessing to model training, evaluation, and deployment.

📘 Introduction

Brain tumor classification is a crucial task in medical imaging, aimed at identifying the presence of brain tumors in MRI scans. This project leverages the VGG19 architecture and deep learning techniques to build a highly accurate classifier.

🛠️ Tech Stack
This project is developed with the following technologies:

TensorFlow 🟦: Framework for building and training deep learning models.
Keras 🔧: High-level API for creating and training models, enabling the use of VGG19 as a pretrained model.

VGG19 🖼️: Deep convolutional neural network architecture used as a feature extractor.

OpenCV 🎥: Used for image preprocessing, such as grayscale conversion and contour detection.

Python 🐍: Programming language for data handling, model building, and evaluation.

📂 Dataset

This project uses a dataset of brain MRI scans, containing labeled images for tumor and non-tumor classes. Ensure your dataset is organized with the following structure:

📎 Dataset Drive Link: [https://drive.google.com/drive/folders/13zkMuZBq4oPrB7fEpYQZDt_2JFUsa3Rg?usp=sharing]

🔍 Data Preprocessing

The following preprocessing steps are applied:

Grayscale Conversion 🎨: Converts images to grayscale.

Gaussian Blur 💨: Reduces noise in images.

Thresholding ⚖️: Enhances image contrast.

Contour Detection 🔍: Identifies regions of interest in the MRI scans.

🧩 Model Architecture

The model is based on the VGG19 architecture, pretrained on the ImageNet dataset, and fine-tuned for binary classification. Here's a summary of the approach:

Feature Extraction 🔍: Convolutional layers of VGG19 are used to extract meaningful features.

Fully Connected Layers 🔗: Custom fully connected layers are added to adapt VGG19 for binary classification.

Activation Function ⚙️: Softmax activation for the output layer.

Optimization 🧬: Model is compiled with the Adam optimizer and binary cross-entropy as the loss function.

📊 Results
The model achieved impressive metrics on the test set:

Accuracy 🎯: 80%

🚀 Deployment

The model is deployed using Flask to enable easy access to predictions.The UI is attached Below.

![Screenshot 2024-11-15 112633](https://github.com/user-attachments/assets/cbc26c77-9b20-48a4-b7a2-df533062046c)








