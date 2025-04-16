# Real-Time Sign Language Detection

This project demonstrates how to build a real-time sign language detection system using TensorFlow's Object Detection API and Python. The system captures video input, processes it in real-time, and identifies specific sign language gestures.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Image Collection](#image-collection)
- [Labeling Images](#labeling-images)
- [Training the Model](#training-the-model)
- [Real-Time Detection](#real-time-detection)
- [Conclusion](#conclusion)

## Introduction

The goal of this project is to create an efficient and accurate real-time sign language detector that can be used for various applications, including communication aids for the hearing impaired.

## Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.x
- TensorFlow
- OpenCV
- LabelImg (for labeling images)

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/vrandamanihar/sign-language-detection.git
   cd sign-language-detection
   
Image Collection
To train the model, you need to collect images of the sign language gestures. Use a webcam to capture images and save them in designated folders for each gesture.

Labeling Images
Organize your images into folders corresponding to each gesture.
Use the LabelImg tool to label your images. Save the annotations in Pascal VOC format.
Training the Model
Update the label map to include your gesture labels.
Configure the training parameters in the config.py file.
Run the training script:
Copy
python train.py
Monitor the training process and metrics to optimize performance.
Real-Time Detection
Once the model is trained, you can run the real-time detection script:

Copy
python detect.py
This script will use your webcam to detect sign language gestures in real-time.

Conclusion
This project provides a foundation for developing a real-time sign language detection system. You can further enhance the model by experimenting with different architectures, hyperparameters, and datasets.

Acknowledgments
TensorFlow Object Detection API
OpenCV
LabelImg
