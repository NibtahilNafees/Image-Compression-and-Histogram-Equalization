# Image-Compression-and-Histogram-Equalization

This repository contains Python code to perform image compression and histogram equalization on grayscale images, comparing custom implementations with OpenCV's built-in functions.

**Requirements:**

Python 3.x,
 OpenCV,
 NumPy,
 Matplotlib,
 PIL (Python Imaging Library).

**Functionality**

**Custom Image Compression and Histogram Equalization:**

Implementations of histogram equalization (my_histEqu) and image compression (my_imageCompression) without using OpenCV's built-in functions.
my_histEqu(img, bins=256): Performs histogram equalization on a grayscale image.
my_imageCompression(image, cFactor): Compresses the image using histogram equalization and downsampling.

**Displaying Histograms:**

histograms(gray_image, compressed_image): Displays histograms of the original and compressed images.

**Comparison with OpenCV:**

img_compressionCV(image, cFactor): Uses OpenCV's equalizeHist function for image compression.
Compares results of custom implementation with OpenCV's results using histograms.
