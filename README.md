# Edge-detection--Computer-Vision-
This repository provides an implementation of edge detection algorithms using the Canny and Sobel methods. 
The Canny edge detection algorithm is a popular technique for detecting edges in digital images, 
while the Sobel method is a simple gradient-based approach for edge detection.

# Usage
(1)Ensure you have the required dependencies installed. You can install them using the following command:
   pip install -r requirements.txt
(2) Place the input image you want to perform edge detection on in the images directory.
(3) Run the edge detection script:
  python edge_detection.py --image_path images/input_image.jpg
Replace 'input_image.jpg' with the filename of your input image.
(4) The script will generate two output images: 'canny_edges.jpg' and 'sobel_edges.jpg'. 
These images will contain the detected edges using the Canny and Sobel methods, respectively.

# Requirements
Python 3.x, Jupyter notebook

# Acknowledgments
-The Canny edge detection algorithm was introduced by John F. Canny in his paper "A Computational Approach to Edge Detection" (1986).
-The Sobel method was first described by Irwin Sobel and Gary Feldman in their paper "A 3x3 Isotropic Gradient Operator for Image Processing" (1968).

# License
This code is provided under the MIT License, allowing you to use, modify, and distribute it freely.



