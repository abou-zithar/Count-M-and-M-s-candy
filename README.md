# M&M Candy Color Detection using OpenCV
This repository contains a Python script that uses the OpenCV library to detect and count the colors of M&M candies in an image. The script processes images, identifies different color regions in the candies, and provides a count of each color.

## Table of Contents
Prerequisites
Usage
Functionality
Example
License
Prerequisites
Python 3.x
OpenCV (cv2) library
Numpy library
google.colab.patches module (if using Google Colab)
imutils library

## You can install the required libraries using the following command:


### pip install opencv-python numpy imutils
## Usage
Clone or download this repository to your local machine.

Place the image of M&M candies you want to analyze in the same directory as the script.

Open a terminal or command prompt and navigate to the repository's directory.

Run the script using the following command:


python m_and_m_color_detection.py
Replace m_and_m_color_detection.py with the actual name of the script if it's different.

## Functionality
The script performs the following steps:

Reads an input image of M&M candies.
Preprocesses the image by resizing it to a fixed size and converting it to the HSV color space.
Creates color masks for various M&M candy colors (red, blue, green, yellow, brown, and orange) using predefined color ranges.
Detects the contours of each color in the image and draws rectangles around the detected regions.
Counts the instances of each color and displays the counts on the output image.
Calculates and displays the total count of all detected colors.
## Example
For a detailed example of how to use the script, please refer to the m_and_m_color_detection.py file in this repository.

## License
This project is licensed under the MIT License.

