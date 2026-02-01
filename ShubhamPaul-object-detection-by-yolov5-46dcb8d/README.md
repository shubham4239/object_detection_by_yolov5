# object-detection-by-yolov5


This repository documents my week-by-week progress on a computer vision project focused on **pedestrian detection, object tracking**. It contains concise weekly reports for Weeks 1–4, followed by a **final applied assignment** that integrates detection and tracking into one end-to-end pipeline.


## Project goal

Build a strong practical understanding of **computer vision for detection and tracking**, then apply these techniques to model **normal pedestrian motion** simulating real-world surveillance deployments.


## Repo layout

```
Object-Tracking
├── README.md
├── Week1
│   └── Week1.md
├── Week2
│   └── Week2.md
├── Week3
│   └── Week3.md
├── Week4
│   └── Week4.md
└── Final-Results
    ├── results_12
    ├── videos_processed
    ├── yolov5final.ipynb
    └── object_tracking.ipynb

```

Each `WeekX.md` contains:

* short overview of the week
* topics covered and why they matter
* key concepts, datasets, and models used

The `Final-Assignment/` folder contains the **complete integrated implementation**.


## What to expect

### Week 1 — Deep Learning Foundations

* Neural Networks and backpropagation
* Convolutional Neural Networks (CNNs)
* PyTorch-based NN and CNN tutorials
* OpenCV basics for image processing


### Week 2 — Object Detection & YOLOv5

* Object detection fundamentals
* YOLO algorithm and single-stage detectors
* YOLOv5 architecture and variants
* Training YOLOv5 on custom datasets


### Week 3 — Training YOLOv5 on MOT17

* Understanding the MOT17 dataset
* Data preprocessing and annotation conversion
* Training YOLOv5s and YOLOv5m models
* Freezing layers and comparing performance


### Week 4 — Object Tracking 

* Object tracking concepts and evaluation
* Tracking-by-detection pipeline
* DeepSORT-based tracking
* Motion trajectory extraction


## Final Assignment 

* Successfully trained YOLOv5 models for pedestrian detection on MOT17
* Integrated YOLOv5 with DeepSORT for multi-object tracking in videos
* Generated and visualized pedestrian trajectories across frames
* Processed video outputs demonstrating consistent ID assignment and motion continuity

## Dependencies (summary)

* numpy, pandas
* matplotlib
* opencv-python
* torch
* yolov5
* deep-sort-realtime
* jupyter / google colab


## How to review the work

* Read `WeekX/WeekX.md` for conceptual understanding.
* Explore week4/ for the complete detection and tracking pipeline.
* Follow the progression from **foundations → detection → tracking**.


## Status

This repository contains the completed work for **Weeks 1–4** and a **final assignment**, submitted as the **final report and implementation**.

