# Dominant Color Extraction for Image Segmentation

## Overview

A Python-based image segmentation project that uses K-Means clustering to extract dominant colors from an image and create a simplified segmented version.

Each image pixel is treated as a data point with three color features: Red, Green, and Blue (RGB).

## Key Features

* Image loading and RGB conversion
* Pixel-level data preparation
* K-Means clustering with 4 clusters
* Extraction of dominant colors
* Visualization of dominant color swatches
* Image segmentation using cluster assignments
* Comparison of the original and segmented image

## Technologies Used

* Python
* NumPy
* Matplotlib
* OpenCV
* Scikit-learn
* K-Means Clustering
* Jupyter Notebook

## Project Workflow

1. Load the image using OpenCV.
2. Convert the image from BGR to RGB format.
3. Reshape image pixels into a two-dimensional array.
4. Apply K-Means clustering with 4 clusters.
5. Extract the cluster centers as dominant colors.
6. Visualize the extracted color groups.
7. Assign each pixel to its corresponding dominant color.
8. Reshape the pixels to reconstruct the segmented image.

## Project Structure

```text
Dominant-Color-Extraction/
├── Dominant_Color_Extraction.ipynb
├── elephant.jpg
├── README.md
└── .gitignore
```

## Results

The project extracts four dominant colors from the input image and uses them to generate a simplified segmented representation of the original image.

## How to Run

Install the required libraries:

```bash
pip install numpy matplotlib opencv-python scikit-learn
```

Open the Jupyter Notebook and run the cells in order.

The notebook uses `elephant.jpg` as the input image.

## Key Learning

This project demonstrates how unsupervised K-Means clustering can be applied to image pixel data for dominant color extraction and basic image segmentation.
