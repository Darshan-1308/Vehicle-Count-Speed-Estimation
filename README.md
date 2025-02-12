# Vehicle Count and Speed Estimation

This project is designed to estimate the number of vehicles on the road and calculate their speeds using computer vision techniques. The system processes video feeds or real-time camera data to detect and track vehicles. By analyzing frame-by-frame motion, it can provide accurate estimates of vehicle count and speed.

## Features

- **Vehicle Detection**: Detects vehicles in video or camera feeds.
- **Vehicle Counting**: Counts the number of vehicles passing through a defined area.
- **Speed Estimation**: Estimates the speed of each detected vehicle in real-time.
- **Real-Time Processing**: Capable of processing video streams for live monitoring.
- **Data Output**: Displays real-time vehicle count and speed data.

## Technologies Used

- OpenCV
- TensorFlow / YOLO (for vehicle detection)
- Python

## How It Works

1. **Vehicle Detection**: The system uses object detection algorithms (e.g., YOLOV8n) to detect vehicles in each video frame.
2. **Tracking**: Once vehicles are detected, tracking algorithms are applied to follow the vehicles as they move through the frame.
3. **Speed Calculation**: The system calculates speed based on the distance covered by the vehicle between frames and the frame rate of the video.
4. **Vehicle Count**: The system counts vehicles that pass through a predefined line or area of interest within the video feed.
