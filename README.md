# Object-Detection-and-Distance-Measurement-using-Mobile-Net-SSD
Using OpenCV 4.0.1, Python 3.8 and Tensorflow 2.3, object detection and distance measurement in real-time is obtained.
For distance measurement, Triangle Similarity algorithm is used. For more information visit this link : 
https://www.pyimagesearch.com/2015/01/19/find-distance-camera-objectmarker-using-python-opencv/ 
and this repo : https://github.com/Subikshaa/Social-Distance-Detection-using-OpenCV/blob/master/social_distance_detection.py
Webcam is used to capture the video, detect the objects and measure the distance from webcam in real-time.
The mobilenet-ssd model is a Single-Shot multibox Detection (SSD) network intended to perform object detection. This model is implemented using the Caffe* framework. 

## Introduction

What is Object Detection? 
<p> Object detection can be defined as a branch of computer vision which deals with the localization and the identification of an object. Object localization and identification are two different tasks that are put together to achieve this singular goal of object detection. Object localization deals with specifying the location of an object in an image or a video stream, while object identification deals with assigning the object to a specific label, class, or description. Here, object identification is specifically done along with distance measurement. </p>
<b>MobileNet</b> is an object detector released in 2017 as an efficient CNN architecture designed for mobile and embedded vision application. This architecture uses proven depth-wise separable convolutions to build lightweight deep neural networks. For more details about MobileNet SSD's, visit here : https://docs.openvinotoolkit.org/2021.2/omz_models_public_mobilenet_ssd_mobilenet_ssd.html 


![](demo.gif)

## Setup (Packages version)
```
pip install -r requirements.txt
```
## Execute the .ipynb file
```
object & distance.ipynb
```

## Download the demo file
https://bit.ly/3a2vLTU

## Other Object Detection models

https://bit.ly/3tdrzsb


