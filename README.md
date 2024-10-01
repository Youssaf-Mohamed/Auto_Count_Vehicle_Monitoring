# Real-Time Traffic Object Detection and Tracking

## Overview
This project demonstrates real-time object detection and tracking for traffic using the YOLOv8 model and OpenCV. The system identifies and counts cars and trucks moving downwards in a video stream, using a set of defined lines to track their motion. It provides an efficient solution for traffic management and monitoring.

## Technologies Used
- YOLOv8 (Ultralytics)
- OpenCV
- Supervision Library (for video processing)
- SORT Algorithm (for tracking)
- TensorFlow (optional for deep learning integration)

## Features
- **Object Detection**: Identifies cars and trucks in video frames using the YOLOv8 model.
- **Object Tracking**: Tracks the movement of detected objects using the SORT algorithm.
- **Vehicle Counting**: Counts the number of cars and trucks crossing predefined lines in the video.
- **Real-Time Processing**: Operates on real-time video streams to enable live traffic monitoring.

## How It Works
1. The YOLOv8 model is used to detect objects in each frame of the video.
2. Detected objects (cars and trucks) are tracked using the SORT algorithm.
3. Lines are defined in the frame to track vehicle movement.
4. The system counts how many cars and trucks cross these lines moving downwards.

## Setup and Installation

### Requirements
Ensure you have Python 3.8+ installed on your system. Then, install the necessary libraries using the following command:

```bash
pip install -r requirements.txt
