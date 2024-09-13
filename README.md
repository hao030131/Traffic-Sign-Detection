# Traffic-Sign-Detection

## Overview
This project implements a robust traffic sign detection system using color and shape-based techniques. The system is designed to address real-world challenges like varying lighting conditions, occlusions, and noise. The detection pipeline includes preprocessing stages, shape detection algorithms, and evaluation metrics such as IoU (Intersection over Union) and Dice Coefficients to assess the performance.

## Features
### Preprocessing:

Image denoising and contrast enhancement
Scaling for size normalization
HSV thresholding for color segmentation
Edge detection for shape recognition
### Detection Algorithms:

Douglas-Peucker method for shape approximation
Hough Circle Transform for detecting circular shapes (e.g., speed limit signs)
## Evaluation Metrics:

IoU (Intersection over Union) for segmentation accuracy
Dice Coefficient for overlapping region accuracy
## Challenges Addressed:

Varying lighting conditions
Occlusions of traffic signs
Noise in image data
## Technologies
Python
OpenCV for image processing
NumPy for matrix operations
Matplotlib for result visualization
