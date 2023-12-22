# Vehicle Plate Detection System README

## Overview

Welcome to our Vehicle Plate Detection System! This system is designed to detect vehicle license plates in images and videos using the YOLO (You Only Look Once) object detection model. YOLO is a real-time object detection system that can quickly and accurately identify objects in images and videos.

In this README, we'll guide you through the process of using our system to detect license plates in a video. The following command illustrates how to use the system:


## Prerequisites

1-Before using the Vehicle Plate Detection System, ensure that you have installed:

- Python 3.x

2-Then, run this command to install all requirements :

pip install -r Requirements.txt

## Command Usage

3-To detect vehicle license plates in a video, use the following command:


yolo detect predict model=detector.pt source='https://youtu.be/LNwODJXcvt4' imgsz=320



- `model`: Specifies the path to the YOLO pre-trained model weights file.
- `source`: Specifies the source of the video. It can be a file path or a URL.
- `imgsz`: Specifies the image size to be used for detection.

Adjust the `imgsz` parameters based on your specific requirements.

## Output

The system will process the input video and output a new video with bounding boxes around detected license plates. The output video will be saved to the default output location unless specified otherwise.


Happy detecting! 🚗🔍
