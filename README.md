# Real-time-object-detection
🤓Real-time object detection with deep learning and openCV. To build our deep learning-based real-time object detector with OpenCV we will require 
  - access our webcam/video stream in an efficient manner and 
  - apply object detection to each frame.

## ✔Import Libraries --
    - from imutils.video import VideoStream
    - from imutils.video import FPS
    - import numpy as np
    - import argparse
    - import imutils
    - import time
    - import cv2
    
    
#### ____________________________________________________________________________________________________________________________ 
    --prototext : The path to the Caffe prototxt file.
    -- model : The path to the pre-trained model.
    -- confidence : The minimum probability threshold to filter weak detections. The default is 20%.
  
#### For the example code + pre-trained (caffe model) Convolutional Neural Network --
    $ python real_time_object_detection.py \
      --prototxt MobileNetSSD_deploy.prototxt.txt \
      --model MobileNetSSD_deploy.caffemodel
    [INFO] loading model...
    [INFO] starting video stream...
    [INFO] elapsed time: 55.07
    [INFO] approx. FPS: 6.54
    
follow the above steps to see realtime object detection.
- To run the program in Jupyter notebook, comment the argparse segment and you dont have to run it everytime like in terminal. This works fine with Jupyter notebook.

cheerio 🙋🏻‍♀️
