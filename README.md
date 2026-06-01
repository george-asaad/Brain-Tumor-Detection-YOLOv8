# Brain Tumor Detection Using YOLOv8

## Overview

This project uses the YOLOv8 object detection model to identify and localize brain tumors in MRI images. The goal is to assist medical image analysis by providing accurate and efficient tumor detection through deep learning and computer vision techniques.

## Problem Statement

Manual analysis of MRI scans can be time-consuming and challenging, especially when processing large numbers of medical images. This project aims to automate brain tumor detection and localization using state-of-the-art object detection methods.

## Technologies Used

* Python
* YOLOv8
* Ultralytics
* OpenCV
* NumPy
* Matplotlib
* Kaggle

## Project Workflow

1. Data Collection
2. Data Annotation
3. Image Preprocessing
4. Model Training using YOLOv8
5. Validation and Evaluation
6. Tumor Detection and Localization
7. Performance Analysis

## Model Performance

| Metric              | Value        |
| ------------------- | ------------ |
| mAP@0.50            | 96.62%       |
| mAP@0.50:0.95       | 80.46%       |
| mAP@0.70            | 90.40%       |
| Inference Time      | 9.3 ms/image |
| Preprocessing Time  | 1.3 ms/image |
| Postprocessing Time | 0.9 ms/image |

## Results

The model achieved high detection accuracy while maintaining fast inference speed suitable for real-time medical image analysis. YOLOv8 successfully localized brain tumors across multiple MRI images with strong precision and recall performance.

## Future Improvements

* Increase dataset size
* Apply data augmentation
* Hyperparameter optimization
* Model deployment using Flask or FastAPI
* Integration into clinical decision-support systems

## Author

George Asaad
