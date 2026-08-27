# Task - Object Detection and Tracking

## Overview

This project implements object detection and tracking on a video file using **OpenCV**, a pre-trained **YOLO11n** model, and **Deep SORT**.

The system processes the video frame by frame, detects selected objects, tracks them across consecutive frames, and displays bounding boxes, object labels, and tracking IDs.

## Technologies Used

- Python
- OpenCV
- YOLO11n (Pre-trained)
- Deep SORT
- Google Colab

## Objects Tracked

- Person
- Bicycle
- Car
- Motorcycle
- Bus

A confidence threshold of **0.4** is used to filter low-confidence detections.

## Workflow
```text
Input Video
↓
OpenCV
↓
YOLO11n Object Detection
↓
Confidence Filtering
↓
Deep SORT Tracking
↓
Bounding Boxes + Labels + Tracking IDs
↓
Annotated Output Video
```

## Google Drive

The **Google Drive** folder contains the project videos, including the original input video and the processed output video generated after object detection and tracking.

**Google Drive Link:**  
https://drive.google.com/drive/folders/1VTIexpUU0HiUQ_2METD_4tH2XQa_JNTP?usp=sharing

### Contents

- `traffic_video.mp4` — Original input traffic video.
- `traffic_tracked.mp4` — Processed output video with bounding boxes, object labels, and Deep SORT tracking IDs.
