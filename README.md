## DETECTING SPECIFIC LABEL AND COUNT USING YOLO V4 FOR COCO DATASET:


This repository provides an implementation of YOLO V4 algorithm for detecting specific label and count  in videos using the Darknet framework.





















































































## Architecture:

![App Screenshot](https://www.mathworks.com/help/vision/ug/yolov4architecture.png)





YOLOv4's architecture is composed of CSPDarknet53 as a backbone, spatial pyramid pooling additional module, PANet path-aggregation neck and YOLOv3 head. CSPDarknet53 is a novel backbone that can enhance the learning capability of CNN.





![App Screenshot](https://preview.redd.it/udgjuocxen651.jpg?width=1536&format=pjpg&auto=webp&s=28eef4e10e247522d5caeea2b8888c5651c93f23)

## Requirements:
*   Darknet Framework
*   Matplotlib
*   Open cv
*   Pre-trained YOLOv4 weights
*   Numpy


## Setup:
Install the dependencies: pip install opencv-python numpy

Download the YOLOv4 weights file: yolov4.weights

Download the YOLOv4 configuration file: yolov4.cfg

Download the COCO dataset labels file: coco.names
## Test Image:

![SUPERCARBLONDIE_HP](https://github.com/vishwateja19/Detecting-specific-label-and-count-using-Yolo-v4/assets/114558376/647df4cb-403e-484e-8a87-131de93ee9cc)



## Result Image after implementation of yolo v4:

![download (1)](https://github.com/vishwateja19/Detecting-specific-label-and-count-using-Yolo-v4/assets/114558376/d5600434-e16d-4d59-90e7-8c7d7861026b)

## Acknowledgements:

 
This implementation is based on the YOLOv4 implementation . The COCO dataset is provided by Microsoft COCO.









































































