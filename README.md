# Unique Human Detection and Tracking in Videos
This project implements a system to detect and count unique humans in video footage using the YOLO (You Only Look Once) object detection model and object tracking techniques. The goal is to ensure that each person is counted only once, even if they reappear in different frames.

## Features
### Human Detection: Uses YOLOv3 for real-time human detection.
### Unique Human Counting: Ensures that each person is counted only once throughout the video.
### Tracking: Utilizes tracking algorithms to maintain identity across frames.

## Requirements
Python 3.6 or higher
OpenCV
NumPy
SciPy
Matplotlib
Imutils
You can install the required Python packages using pip:

bash
Copy code
pip install opencv-python-headless numpy scipy matplotlib imutils
## Model Files
Ensure you have the following model files:

+ yolov3.weights - Pre-trained YOLOv3 weights.
+ yolov3.cfg - YOLOv3 configuration file.
+ coco.names - File containing the class labels for YOLO (e.g., person).
Download these files from the YOLO website or the official YOLO repository.
