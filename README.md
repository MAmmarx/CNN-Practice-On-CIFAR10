# CIFAR-10 Image Classification with a CNN

📌 Overview
VisionSphere is a Convolutional Neural Network (CNN) trained on the CIFAR-10 dataset. It is capable of classifying images into 10 different categories, including common objects like airplanes, dogs, and ships. Built using Keras, this project demonstrates key deep learning principles for image classification, such as data preprocessing, model architecture design, and training with an Adam optimizer.

🧑‍💻 Objective
The primary goal of this project is to build a robust deep learning model that can accurately classify images from the CIFAR-10 dataset. This project focuses on implementing a practical CNN architecture and evaluating its performance on a standard benchmark dataset.

🛠️ Features
✅ 1. Data Processing

Loads the CIFAR-10 dataset.

Normalizes pixel values by scaling them to the range [0, 1].

One-hot encodes the labels for multi-class classification.

✅ 2. Model Architecture

A Sequential CNN with multiple Conv2D and MaxPooling2D layers.

Includes a Dropout layer to prevent overfitting.

Uses ReLU and Softmax activation functions.

Trained for 30 epochs with the Adam optimizer.

✅ 3. Evaluation

Accuracy is measured on a dedicated test set, achieving approximately 73.27% accuracy.

⚙️ Technologies Used
Python 3

TensorFlow / Keras

NumPy

Pandas

🧪 Installation & Usage
🔹 Requirements

Python (3.8 or above)

Jupyter Notebook / Google Colab

TensorFlow (pip install tensorflow)

📌 Run the Script

Bash

python cifar10_cnn.py
🧑‍🎓 Developed For
Summer Break – Self Learning Project

✍️ About Me
This project was made by myself in summer using self-learned Deep Learning. It helped me understand data preprocessing, model training, and accuracy visualization using real-world image classification.
