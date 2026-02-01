# Week 1 — Object Detection Foundations

## Overview
Week 1 focused on developing a clear conceptual understanding of object detection in computer vision. The objective was to understand how modern deep learning–based detectors work and how YOLO-based models perform object detection efficiently. This week established the theoretical groundwork required for implementing and training YOLOv5 models in later stages of the project.

## Topics Covered

### Basics of Object Detection
- Object detection is the task of identifying objects present in an image and localizing them using bounding boxes.
- Each detected object is associated with a class label and a confidence score.
- The difference between image classification, object detection, and object tracking was studied.
- Object detection acts as a bridge between simple image understanding and advanced video-based tasks such as tracking and object detection.

### YOLO Algorithm Overview
- YOLO (You Only Look Once) is a single-stage object detection algorithm.
- Detection is performed in a single forward pass of the neural network.
- The image is processed as a whole instead of using region proposals.
- Bounding box coordinates and class probabilities are predicted simultaneously.
- This design enables high-speed inference and real-time detection performance.

### YOLOv5 Framework
- YOLOv5 is a PyTorch-based implementation of the YOLO algorithm.
- It provides a modular and flexible architecture for training and inference.
- Anchor boxes are used to predict bounding boxes of varying sizes and aspect ratios.
- The training pipeline includes data preprocessing, loss computation, and optimization.
- Evaluation metrics such as Intersection over Union (IoU) and mean Average Precision (mAP) were studied to assess detection performance.

## Key Learnings
- Object detection combines object localization and classification into a single task.
- YOLO performs detection efficiently using a single-stage approach.
- YOLOv5 offers a practical and scalable framework for custom object detection tasks.
- Detection outputs include bounding box coordinates, confidence values, and class labels.

## Conclusion & Next Steps
Week 1 successfully established a structured understanding of object detection concepts and the YOLO framework. The knowledge gained during this week serves as a base for deeper exploration of YOLOv5 and hands-on object detection workflows.

In the next week, the focus shifts to object detection fundamentals and a more detailed study of YOLOv5.
