# Drowsiness Detection OpenCV 😴 🚫 🚗

[![](https://img.shields.io/github/license/sourcerer-io/hall-of-fame.svg?colorB=ff0000)](https://github.com/akshaybahadur21/Drowsiness_Detection/blob/master/LICENSE.txt)

This code is designed to detect drowsiness in users by monitoring their eyes and issuing alerts when drowsiness is detected.

## Applications 🎯
This system can be particularly useful for individuals who drive for extended periods, as it can help prevent accidents caused by drowsy driving.

### Code Requirements 🦄
The example code is written in Python, and version 2.7 or higher should work.

### Dependencies

1) import cv2
2) import imutils
3) import dlib
4) import scipy

### Description 📌

This project implements a computer vision system that can automatically detect driver drowsiness in real-time video streams and sound an alarm if the driver appears to be drowsy.

### Algorithm 👨‍🔬

Each eye is represented by 6 (x, y)-coordinates, starting at the left corner of the eye (as if you were looking at the person), and then proceeding clockwise around the eye.

The system checks 20 consecutive frames, and if the Eye Aspect ratio is less than 0.25, an alert is triggered.

<img src="https://github.com/akshaybahadur21/Drowsiness_Detection/blob/master/assets/eye1.jpg">


#### Relationship

<img src="https://github.com/akshaybahadur21/Drowsiness_Detection/blob/master/assets/eye2.png">

#### Summing up

<img src="https://github.com/akshaybahadur21/Drowsiness_Detection/blob/master/assets/eye3.jpg">


For more information, [see](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)

### Results 📊

<img src="https://github.com/akshaybahadur21/BLOB/blob/master/drowsy.gif">


### Execution 🐉
To run the code, type `python Drowsiness_Detection.py`

```
python Drowsiness_Detection.py
```

###### Made with ❤️