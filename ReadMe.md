

# Object Detection - Face Mask Detection

With the ongoing impact of COVID-19, ensuring proper usage of face masks has become essential in controlling the virus's spread. This repository contains an object detection solution to identify if individuals are wearing masks correctly, incorrectly, or not at all.

## Overview
This project leverages two cutting-edge object detection algorithms, FASTER-RCNN and YOLO v5, to classify individuals based on their mask usage. The goal is to effectively detect and differentiate between the following classes:
1. **With Mask**
2. **Without Mask**
3. **Mask Worn Incorrectly**

### Key Features
- **Algorithms Used**: FASTER-RCNN and YOLO v5.
- **Dataset**: A diverse dataset containing images labeled into the three mask-related categories.
- **Performance Comparison**: An evaluation of model accuracy and performance between FASTER-RCNN and YOLO v5 using metrics such as precision, recall, and inference time.

### Dataset
The dataset used in this project includes annotated images with three classes:
1. **With Mask**: Images where individuals are wearing masks correctly.
2. **Without Mask**: Images of individuals without any facial masks.
3. **Mask Worn Incorrectly**: Images showing individuals wearing masks incorrectly (e.g., below the nose, under the chin).

### Algorithms
- **FASTER-RCNN**: A region-based convolutional neural network designed for efficient object detection by identifying regions of interest (ROIs) and classifying objects within these regions.
- **YOLO v5**: A state-of-the-art, real-time object detection algorithm that provides fast and accurate predictions by splitting images into grids and predicting bounding boxes and class probabilities directly.

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/BaluHarshavardan99/Face-Mask-Detection.git

**Examples from Dataset:**  

![alt text](https://github.com/BaluHarshavardan99/Object-Detection-Face-Mask-Detection/blob/main/dataset_examples.png)



