# Multi-Face-Detector-Python

Multi-Face Detector is a simple Python application that uses OpenCV to detect and highlight multiple human faces in a given image. The program identifies faces using the Haar Cascade Classifier and draws rectangular boxes around each detected face. This is an ideal beginner project for those learning image processing or computer vision.

🚀 Features:
1.Detects multiple faces in a single image

2.Highlights faces with rectangular boxes

3.Uses OpenCV’s pre-trained Haar cascade for frontal face detection

4.Lightweight and fast

5.Easy to use and modify

📂 How It Works:
This program relies on OpenCV, a powerful open-source computer vision library. Specifically, it uses a Haar Cascade Classifier — a machine learning-based approach where a cascade function is trained with a lot of positive and negative images to detect objects.

Key Components:
import cv2-
This line imports the OpenCV library in Python. OpenCV (cv2) provides various functions for image and video processing. In this project, it's used to:

1.Load images

2.Convert color formats

3.Detect faces

4.Draw rectangles around detected areas

haarcascade_frontalface_default.xml:
This is a pre-trained XML file included in OpenCV. It contains data for detecting frontal human faces using the Haar feature-based cascade classifier. This model is trained on thousands of positive (face) and negative (non-face) images. The classifier can efficiently scan an image and locate face-like patterns.

haarcascade_frontalface_default.xml
This is a pre-trained XML file included in OpenCV. It contains data for detecting frontal human faces using the Haar feature-based cascade classifier. This model is trained on thousands of positive (face) and negative (non-face) images. The classifier can efficiently scan an image and locate face-like patterns.
