# Week 3 — Training YOLOv5 on the MOT17 Dataset

## Overview
Week 3 focused on the practical implementation of training YOLOv5 models on a real-world dataset. The MOT17 dataset was used to train a pedestrian detection model, with emphasis on understanding the dataset structure, preprocessing requirements, and the training workflow. This week connected object detection theory with hands-on model training and evaluation.

## Topics Covered

### MOT17 Dataset Understanding
- MOT17 is a benchmark dataset designed for pedestrian detection and multi-object tracking.
- The dataset contains real-world video sequences with challenges such as crowd density, occlusions, camera motion, and varying lighting conditions.
- Each video sequence appears in multiple versions due to different precomputed detectors, while sharing the same ground truth annotations and image frames.
- Only one version per sequence was selected to avoid data duplication during training.

### Data Preprocessing
- Conversion of MOT17 ground truth annotations to YOLO format.
- Transformation of bounding boxes from top-left coordinate format to normalized center-based format.
- Organization of data into training, validation, and testing folders.
- Creation of a `data.yaml` file specifying dataset paths, number of classes, and class names.

### YOLOv5 Model Training
- Training multiple YOLOv5 variants for pedestrian detection.
- Models trained included:
  - YOLOv5s
  - YOLOv5m
  - YOLOv5m with selected layers frozen
- Use of transfer learning to leverage pre-trained weights.
- Comparison of training behavior across different model configurations.

### Model Comparison and Analysis
- Evaluation of detection quality across different YOLOv5 models.
- Observation of performance differences in crowded scenes.
- Analysis of trade-offs between detection accuracy and computational efficiency.



## Key Learnings
- Dataset understanding and preprocessing are critical for successful model training.
- YOLOv5 can be effectively trained for pedestrian detection using MOT17.
- Freezing early layers helps retain general visual features while adapting to a specific task.
- Model selection depends on the balance between accuracy and inference efficiency.

## Conclusion & Next Steps
Week 3 successfully demonstrated the complete workflow of training YOLOv5 models on a real-world dataset. The trained pedestrian detector serves as the foundation for object tracking and behavior analysis.

In the next week, the focus will shift to object tracking and object detection using the trained YOLOv5 models.
