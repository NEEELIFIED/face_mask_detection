# face_mask_detection
This project focuses on building a Face Mask Detection System using Deep Learning techniques with the VGG16 Convolutional Neural Network (CNN) architecture. The model aims to accurately classify whether a person is wearing a mask or not wearing a mask, contributing to public health and safety measures.

This project implements a Face Mask Detection System using Deep Learning techniques with the VGG16 Convolutional Neural Network (CNN) architecture. The model is trained to detect whether a person is wearing a mask or not wearing a mask from images and real-time webcam feeds.

🧠 Overview

In the wake of the global pandemic, automatic mask detection has become an essential computer vision task. This project leverages transfer learning with VGG16, a pre-trained model on ImageNet, to achieve efficient and accurate mask classification with limited data and computational cost.

Unlike publicly available datasets, the dataset used in this project is personally curated — I manually collected images of people with and without masks from the internet to make the training data more realistic and diverse.

⚙️ Features

Deep Learning model built on VGG16 architecture

Transfer Learning applied for efficient training

Binary classification: Mask 😷 / No Mask 🙅‍♂️

Trained on a custom dataset created manually

Real-time face detection integrated using OpenCV

Achieved over 92% accuracy without data augmentation

🧩 Tech Stack

Python

TensorFlow / Keras

OpenCV

NumPy, Matplotlib, Pandas

Jupyter Notebook

📊 Model Details

Base Model: VGG16 (pre-trained on ImageNet)

Optimizer: Adam

Loss Function: Binary Cross-Entropy

Metrics: Accuracy

Epochs: 5 (tunable)

Accuracy Achieved: ~92% on validation data

The model effectively distinguishes between masked and unmasked faces, even under varying lighting conditions and face orientations.

📁 Dataset & Files

Dataset: Personally collected images of masked and unmasked individuals from various internet sources.
Source code:- file already uploaded


