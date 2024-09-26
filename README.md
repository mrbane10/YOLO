# YOLOv2 Object Detection Model in Keras

This repository contains an implementation of the YOLOv2 (You Only Look Once) object detection model using Keras and TensorFlow. YOLOv2 is a real-time object detection algorithm known for its efficiency in detecting multiple objects in an image by predicting bounding boxes and class probabilities for each object.

## Features:
- **YOLOv2 Architecture**: Implements the full YOLOv2 architecture with a Darknet19 backbone.
- **Anchor Boxes**: Supports pre-defined anchor boxes for bounding box predictions.
- **Custom Loss Function**: Includes the YOLOv2 localization loss for object detection.
- **Box Prediction**: Converts feature maps to bounding box predictions using the provided anchors.
- **Non-Maximum Suppression (NMS)**: Filters overlapping boxes to return the best prediction for each object.

## Usage:
- Build and train the YOLOv2 model for object detection tasks on custom datasets.
- Supports VOC dataset anchors and classes for easy integration.

## Requirements:
- Keras
- TensorFlow

## Notes:
- This codebase includes necessary functions for preprocessing, model architecture, and inference.

## License
This project is licensed under the MIT License.
