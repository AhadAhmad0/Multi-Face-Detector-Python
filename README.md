# Multi Face Detector

A Python script that detects multiple faces in a static image using OpenCV's Haar Cascade classifier and draws bounding boxes around each detected face.

## Features

- Detects multiple faces simultaneously in a single image
- Draws blue bounding boxes around each detected face
- Uses OpenCV's pretrained Haar Cascade classifier
- Works on any static image

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)

Install dependencies:
```bash
pip install opencv-python
```

## Usage

```bash
git clone https://github.com/AhadAhmad0/Multi-Face-Detector-Python.git
cd Multi-Face-Detector-Python
python MultiFace_Detector.py
```

Place your image in the project folder and update the `cv2.imread()` filename in the script. Make sure `haarcascade_frontalface_default.xml` is in the same directory.

## How It Works

The image is converted to grayscale, then passed to `detectMultiScale()` which scans for face-like patterns. Bounding boxes are drawn on the original image for each detection.

## Author

**Ahad Ahmad** — [@AhadAhmad0](https://github.com/AhadAhmad0)
