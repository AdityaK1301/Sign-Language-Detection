# Sign-Language-Detection
This project implements a real-time sign language detection system using TensorFlow and OpenCV. It leverages a pre-trained object detection model (SSD MobileNet V2 FPNLite) fine-tuned to recognize five American Sign Language (ASL) gestures: Hello, Yes, No, Thank You, and I Love You. The system captures video input from a webcam, processes it, and displays bounding boxes with labels for detected signs in real-time.

## Features

Image Collection: Captures images for each sign using a webcam, organizing them into labeled directories.

Data Preparation: Generates TFRecord files and label maps for training and evaluation.

Model Training: Fine-tunes a pre-trained SSD MobileNet V2 FPNLite model on custom sign language data.

Real-Time Detection: Uses a webcam to detect and classify sign language gestures in real-time with visualized bounding boxes.

## Pre-Requisites

Python 3.9

TensorFlow 2.x

OpenCV (opencv-python)

TensorFlow Object Detection API

## Cloning this repo

```bash
git clone https://github.com/your-username/Sign-Language-Detection.git
cd Sign-Language-Detection
```

## Install Dependencies

```bash
pip install tensorflow opencv-python numpy
```

## Set Up TensorFlow Object Detection API

```bash
cd Tensorflow
git clone https://github.com/tensorflow/models
```

## Future Improvements
Expand the dataset with more signs and images for better accuracy.

Optimize the model for faster real-time performance.

Add support for additional sign languages or gestures.
