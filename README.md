# object-detection and classification
Description:
This project focuses on implementing a machine learning model using MobileNet SSD for object detection and classification. The model utilizes computer vision techniques to identify and categorize objects within images or video streams.

Requirements:
Python 3.x
OpenCV
NumPy
XML.etree.ElementTree
Jupyter Notebook (for accuracy evaluation)


Usage:
To use the object detection model:

Load the pre-trained MobileNet SSD model.
Configure the model with appropriate input settings.
Run the detection code on images or video files.

File Structure:
object detection.py: Contains the primary code for object detection using MobileNet SSD.
Labels.txt: File containing class labels.
frozen_inference_graph.pb: Pre-trained model file.
ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt: Configuration file.
