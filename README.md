# Persian-ALPR-System
This project implements an end-to-end Persian Automatic License Plate Recognition (ALPR) system using deep learning and computer vision techniques. The system detects vehicle license plates and extracts plate characters from real-world images of Iranian vehicles.
Dataset

A custom dataset of Iranian vehicle license plates was collected and annotated using Roboflow. Images include various lighting conditions, viewing angles, and image qualities to improve model robustness.

Data Augmentation

The following augmentation techniques were applied:

Rotation
Brightness and contrast adjustment
Gaussian blur
Noise injection
Random cropping
Methodology
Image acquisition
License plate detection using YOLOv8
Plate extraction and preprocessing
Character recognition using EasyOCR
Levenshtein-distance-based text correction
Performance evaluation
Technologies
Python
YOLOv8
OpenCV
EasyOCR
NumPy
Roboflow
Results

The system successfully detects and recognizes Persian license plates under varying real-world conditions, including different lighting environments and camera angles.
