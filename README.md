# FetalVision: AI-Enabled Real-Time Fetal Biometry Detection in 2D Ultrasound

FetalVision is a project aimed at leveraging deep learning models for real-time fetal biometry estimation and abnormality detection using 2D ultrasound images. This repository contains implementations of two deep learning models: U-Net and FCN, trained on a custom dataset for this specific task.

## Introduction

Ultrasound imaging is a widely used diagnostic tool in obstetrics for monitoring fetal development and detecting abnormalities. Fetal biometry involves measurements of fetal anatomy such as head circumference, femur length, and abdominal circumference, which are crucial for assessing fetal growth and well-being. Traditional manual measurements can be time-consuming and subjective, motivating the need for automated and accurate methods.

## Features

- Real-time fetal biometry estimation
- Abnormality detection in 2D ultrasound images
- U-Net and FCN models for semantic segmentation
- Custom dataset for training and evaluation


## Dataset

The dataset utilized for fetal head circumference, obtained from Kaggle, was divided into three main sets: training, testing, and validation. Each set consisted of three directories: "images," "annotations," and "labels." The training set contained a total of 699 files, while the testing set had 101 files, and the validation set had 199 files. Overall, we utilized 999 ultrasound images in our project.

Link to the dataset: [Fetal Head Circumference Dataset](https://www.kaggle.com/datasets/theunkovvn/fetal-head-circumference)

## Requirements

- Python 3
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- scikit-learn

  

