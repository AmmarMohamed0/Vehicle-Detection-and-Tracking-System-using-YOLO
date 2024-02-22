# Vehicle-Detection-and-Tracking-System-using-YOLO

## Description

This project implements a vehicle detection and tracking system using the YOLO (You Only Look Once) object detection model. The main components of the system include:

- **Object Detection**: Utilizes the YOLO model to detect vehicles in real-time from a video stream.
- **Object Tracking**: Implements a tracking algorithm to follow the detected vehicles across frames.
- **Speed Estimation**: Estimates the speed of vehicles by tracking their movement over time.
- **Directional Counting**: Counts vehicles moving in both directions by defining virtual lines in the video frame.

The code structure is organized as follows:

- `vehicle_tracker.ipynb`: The main script that integrates object detection, tracking, and counting functionalities.
- `tracker.py`: Contains the implementation of the tracking algorithm.
- `yolov8s.pt`: Pre-trained YOLO model weights for vehicle detection.
- `coco.txt`: List of class names used by the YOLO model.

## Usage

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/AmmarMohamed0/Vehicle-Detection-and-Tracking-System-using-YOLO.git
