# face_mask_detector
# Face Mask Detection System

## Overview

This project is a real-time Face Mask Detection System developed using Python, OpenCV, and a Convolutional Neural Network (CNN). The application captures video from a webcam, detects faces in each frame, and classifies whether a person is wearing a face mask or not.

The project demonstrates the practical application of computer vision and deep learning techniques for image classification and real-time video processing.

## Features

* Real-time face detection using a webcam
* Face mask classification using a trained CNN model
* Live prediction display on video frames
* Simple and lightweight implementation
* Suitable for learning computer vision and deep learning concepts

## Technologies Used

* Python
* OpenCV
* TensorFlow / Keras
* NumPy
* Convolutional Neural Networks (CNN)

## Project Structure

```text
face_mask_detector/
│
├── webcam_mask.py
├── face_mask_cnn_model.h5
├── face_mask_prediction_cnn.mp4
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/Praney1409/face_mask_detector.git
cd face_mask_detector
```

Install the required dependencies:

```bash
pip install opencv-python tensorflow numpy
```

## Usage

Run the application using:

```bash
python webcam_mask.py
```

The webcam will start automatically and display the prediction results in real time.

## How It Works

1. The webcam captures live video frames.
2. Faces are detected from each frame using OpenCV.
3. The detected face region is preprocessed and passed to the trained CNN model.
4. The model predicts whether the person is wearing a mask or not.
5. The prediction is displayed on the video feed.

## Model

The face mask classifier is based on a Convolutional Neural Network trained to distinguish between two classes:

* With Mask
* Without Mask

The trained model is stored in:

```text
face_mask_cnn_model.h5
```

## Demonstration

A sample demonstration video of the system is included in the repository:

```text
face_mask_prediction_cnn.mp4
```

## Future Enhancements

* Improve model accuracy with a larger dataset
* Support detection of multiple faces simultaneously
* Deploy the application as a web-based solution
* Integrate alert and notification systems
* Optimize performance for edge devices

## Author

Praney Sanotra

B.Tech in Electronics and Communication Engineering

DAV Institute of Engineering and Technology

## License

This project is developed for educational and learning purposes.
