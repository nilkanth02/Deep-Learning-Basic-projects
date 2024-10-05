
# Face Detection App 👁️

A simple yet powerful face detection tool powered by OpenCV! Detect faces in images and in real-time with just a few lines of code.

## Features

- **Static Image Detection**: Analyze and detect faces in your images.
- **Real-Time Detection**: Use your webcam for instant face tracking.

## Getting Started

### Requirements

- Python 3.x
- OpenCV: Install with `pip install opencv-python`

### Quick Usage

1. **Detect Faces in an Image**:
   ```python
   import cv2
   # Load Haar cascade and image
   face_cascade = cv2.CascadeClassifier('haarcascade_frontalface_default.xml')
   img = cv2.imread('girl.jpeg')
   # Detect and display faces...
   ```

2. **Real-Time Detection**:
   ```python
   import cv2
   # Load Haar cascade and start webcam
   cap = cv2.VideoCapture(0)
   # Detect faces in frames...
   ```



## Acknowledgments

Thanks to [OpenCV](https://opencv.org/) for the amazing library!


