# Week 2 — Object Detection and YOLOv5

## Overview
Week 2 focused on understanding object detection in greater depth and studying the YOLOv5 framework in detail. The aim of this week was to move from conceptual understanding to practical knowledge of how modern object detectors are structured, trained, and evaluated. Emphasis was placed on understanding YOLOv5’s architecture and its application to real-time object detection tasks.

## Topics Covered

### Object Detection Fundamentals
- Object detection as a supervised learning problem involving labeled bounding boxes.
- Difference between traditional sliding-window approaches and deep learning–based detectors.
- Role of feature extraction and multi-scale detection in identifying objects of different sizes.
- Importance of datasets and annotations in training accurate detection models.

### YOLO Algorithm
- YOLO as a single-stage object detection approach.
- Image divided into grids for prediction.
- Simultaneous prediction of bounding boxes and class probabilities.
- Trade-off between speed and accuracy in real-time detection systems.

### YOLOv5 Architecture
- Backbone network used for feature extraction.
- Neck structure for multi-scale feature aggregation.
- Detection head responsible for final bounding box and class predictions.
- Different YOLOv5 model variants (small, medium, large) and their performance trade-offs.

### Training and Inference in YOLOv5
- Use of pre-trained weights for transfer learning.
- Training on custom datasets using configuration files.
- Role of hyperparameters such as learning rate, batch size, and image resolution.
- Inference pipeline and interpretation of detection outputs.

## Key Learnings
- YOLOv5 provides an efficient end-to-end pipeline for object detection.
- Single-stage detectors enable fast inference suitable for real-time applications.
- Transfer learning significantly reduces training time and data requirements.
- Model selection involves balancing detection accuracy and computational cost.

## Conclusion & Next Steps
Week 2 built practical understanding of object detection using the YOLOv5 framework. The concepts learned during this week prepare the project for hands-on training of YOLOv5 models on real-world datasets.

In the next week, the focus will move to training YOLOv5 on the MOT17 dataset and analyzing detection performance.
