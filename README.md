# Hand_Gesture_Recognition
# Hand Gesture & Hand Shape Recognition

A real-time computer vision project that detects and recognizes hand gestures and hand shapes using a webcam.

## Features

* Real-time hand detection
* 21 hand landmark detection using MediaPipe
* Real-time hand gesture and shape recognition
* Webcam-based detection
* No dataset or model training required
* Simple and lightweight implementation

## Technologies Used

* Python
* OpenCV
* MediaPipe Tasks API
* Math

## Supported Gestures

* Open Palm
* Fist
* Thumbs Up
* Thumbs Down
* Victory
* Pointing Up
* Pinch
* Rock
* Call Me
* I Love You
* Two Fingers
* Three Fingers
* Four Fingers

## Project Structure

```text
Hand_Gesture_Recognition/
│
├── hand_gesture.py
├── hand_landmarker.task
└── README.md
```

## Installation

Install the required libraries:

```bash
pip install opencv-python mediapipe
```

## How to Run

```bash
python hand_gesture.py
```

The webcam will open automatically. Show your hand in front of the camera to detect the gesture.

Press `Q` to exit.

## Objective

The objective of this project is to develop a real-time hand gesture and hand shape recognition system using computer vision and MediaPipe hand landmarks.

## Future Scope

* Add more hand gestures
* Support two-hand gesture recognition
* Gesture-based computer control
* Voice output for detected gestures
* Integration with Machine Learning models

## Author

**Arun Kumar**

B.Tech CSE (Artificial Intelligence)
