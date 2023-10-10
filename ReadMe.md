

**Object Detection - Face Mask Detection**
With the prevalence of COVID-19, in order to control its spread, an algorithm to detect if one is wearing
a facial mask is important. This repository contains code for object detection to detect the proper usage of masks by individuals.

There are three classes in this dataset - 
1) With mask;
2) Without mask;
3) Mask worn incorrectly.

Two different algorithms were tested - 
1) FASTER-RCNN
2) YOLO v5

**Examples from Dataset:**  

![alt text](https://github.com/BaluHarshavardan99/Object-Detection-Face-Mask-Detection/blob/main/dataset_examples.png)

**Annotation Example:**  

![alt text](https://github.com/BaluHarshavardan99/Object-Detection-Face-Mask-Detection/blob/main/annotations.jpg)

**Faster RCNN - Optimizer: SGD; Batch Size: 4** 

![alt text](https://github.com/BaluHarshavardan99/Object-Detection-Face-Mask-Detection/blob/main/SGD_EPOCHS_B4.png)

**Faster RCNN - Optimizer: SGD; Batch Size: 16**  

![alt text](https://github.com/BaluHarshavardan99/Object-Detection-Face-Mask-Detection/blob/main/SGD_B16_RESULTS.png)


**Faster RCNN - Optimizer: Adam; Batch Size:16**   

![alt text](https://github.com/BaluHarshavardan99/Object-Detection-Face-Mask-Detection/blob/main/adam_b16_epochs.png)


**Faster RCNN Predictions vs Target:**  
![alt text](https://github.com/BaluHarshavardan99/Object-Detection-Face-Mask-Detection/blob/main/Faster%20RCNN%20Predictions.png)





