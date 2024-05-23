# Hough-Transform
This repository contains an implementation of the Hough Transform algorithm in Python, utilizing OpenCV and Matplotlib libraries. The Hough Transform is a technique used in image processing to detect shapes, particularly lines or curves. In this implementation, we focus on detecting straight lines in an image.

Getting Started
To use this code, ensure you have Python installed on your system along with the required libraries:

cv2: OpenCV for image processing.
numpy: Numerical computing library for Python.
matplotlib: Plotting library for Python.

The provided Python code implements the Hough Transform, a fundamental technique in image processing for detecting geometric shapes, particularly lines, within an image. The code begins by reading an input image and converting it to grayscale. Subsequently, it applies Gaussian blur and the Canny edge detection algorithm to identify potential edge points. These edge points are then transformed into a parameter space (the Hough space) where each point represents a possible line in the original image. By accumulating votes from edge points that could lie on a particular line, the algorithm effectively detects lines even in the presence of noise or discontinuities. Finally, the algorithm identifies the most prominent lines by thresholding the accumulator matrix and draws them back onto the original image. This code provides a comprehensive illustration of the Hough Transform's implementation, showcasing its utility in various image processing tasks requiring robust line detection.
