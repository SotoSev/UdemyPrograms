# 🐶🐱 CNN for Image Classification (Dogs vs Cats)

This project implements a Convolutional Neural Network (CNN) for image classification, specifically designed to predict whether an input image contains a dog or a cat.

## 📌 Project Overview

The model is trained using labeled images of dogs and cats. The dataset is split into training and testing sets to evaluate the performance of the network on unseen data.

To ensure consistency and proper learning, all images are resized to a fixed resolution of 64 × 64 pixels before being fed into the model. This preprocessing step is crucial, as CNNs require uniform input dimensions.

## 🧠 Model Details

- Architecture: Convolutional Neural Network (CNN)

- Input size: 64 × 64 RGB images

- Task: Binary image classification (Dog vs Cat)

## ⚙️ Image Preprocessing

- Images are resized to (64, 64) to maintain consistent input size.

- Pixel values are scaled appropriately before training.

- The image size can be increased for potentially better accuracy, but this will:

-- Increase computational cost

-- Increase training time

## 📈 Performance Considerations

- Smaller image sizes → faster training, lower resource usage

- Larger image sizes → potentially higher accuracy, slower training

## 📂 Repository Context

This project is one of five projects included in a larger Udemy deep learning course repository and serves as a practical example of applying CNNs to real-world image classification tasks.

## 🚀 Possible Improvements

- Increase image resolution

- Add data augmentation

- Experiment with deeper CNN architectures

- Use transfer learning (e.g., VGG16, ResNet)


