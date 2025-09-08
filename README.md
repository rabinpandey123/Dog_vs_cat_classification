🐶🐱 Dog vs Cat Image Classification using CNN
📌 Overview

This project implements a Convolutional Neural Network (CNN) to classify whether an input image is of a dog 🐶 or a cat 🐱.
The model is trained using TensorFlow/Keras and achieves high accuracy on unseen images.

🚀 Features

Preprocessing of images (resizing, normalization, augmentation).

Custom CNN model for binary image classification.

Visualization of training & validation accuracy/loss.

Testing on new images with real-time predictions.

📂 Dataset

We use the Cat and Dog dataset from Kaggle:

🔗 Kaggle Dataset: Cat and Dog

You need to download the kaggle.json file by creating the new API token into the official kaggle websites: https://www.kaggle.com/datasets

🏗 Model Architecture

The CNN consists of:

Convolutional Layers (feature extraction)

MaxPooling Layers (downsampling)

Flatten Layer (2D → 1D)

Fully Connected Dense Layers (classification)

Sigmoid Output Layer (binary classification: Cat or Dog)
