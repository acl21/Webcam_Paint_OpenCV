### [UPDATE]: I will not be responding to issues or emails related to this repo anymore as I am currently occupied with other research commitments. Also, the libraries used are pretty old and outdated. Thank you.

# Webcam Paint Using OpenCV [![](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/akshaychandra21/Webcam_Paint_OpenCV/blob/master/LICENSE.txt)

This code helps you track an object-of-interest to draw colored lines on the screen (just like the Paint application but using the webcam, which makes it both awesome and harder to draw simple things).

## Working Example
<img src="https://github.com/akshaychandra21/Webcam_Paint_OpenCV/blob/master/demo.gif">

## Project Description
This Python application uses OpenCV library to track any blue object in the frame (bottle cap in my case) and uses the detected object to draw colored lines (Blue, Green, Red and Yellow).

To perform video tracking an algorithm analyzes sequential video frames and outputs the movement of targets between the frames. There are a variety of algorithms, each having strengths and weaknesses. Considering the intended use is important when choosing which algorithm to use. There are two major components of a visual tracking system: target representation and localization, as well as filtering and data association.

Video tracking is the process of locating a moving object (or multiple objects) over time using a camera. It has a variety of uses, some of which are: human-computer interaction, security and surveillance, video communication and compression, augmented reality, traffic control, medical imaging and video editing.

For more information, [see](http://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_tutorials.html).

## Code Requirements
The code is in Python (version 3.6 or higher). You also need to install OpenCV library.

## Code Explanation
I have written [this tutorial post on medium](https://medium.com/@akshaychandra21/dbe356ab5d6c) explaining the code.

## Execution
To run the code, type
```
python Webcam_Paint_OpenCV.py
```
