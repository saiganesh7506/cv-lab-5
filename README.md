# Image Slicing With and Without Background

## Overview

This project demonstrates intensity-level slicing of a grayscale image using Python, OpenCV, NumPy, and Matplotlib. It highlights pixels within a specified intensity range and displays the results with and without the original background.

## Objective

To perform image slicing by selecting pixels whose grayscale intensity values fall within a specified range (100–200).

## Technologies Used

* Python
* OpenCV
* NumPy
* Matplotlib
* Google Colab / Jupyter Notebook

## Methodology

### 1. Image Loading

The input image is loaded in grayscale using OpenCV.

### 2. Intensity Range Selection

The minimum and maximum intensity values are set as:

* Minimum intensity: 100
* Maximum intensity: 200

### 3. Image Slicing Without Background

A black image is created, and pixels within the selected intensity range are highlighted in white (255). Pixels outside the range remain black.

### 4. Image Slicing With Background

A copy of the original image is created. Pixels within the selected intensity range are highlighted in white, while other pixels retain their original intensity values.

## Input Image

The notebook uses the following image path:

`/content/cvlab5.jpg`

Upload the image to Google Colab or modify the path according to your local environment.

## How to Run

1. Clone or download this repository.
2. Open the `.ipynb` notebook in Google Colab or Jupyter Notebook.
3. Upload the required input image.
4. Run all cells sequentially.
5. Observe the original and sliced images.

## Expected Output

The notebook displays three images:

1. Original Image
2. Image Slicing Without Background
3. Image Slicing With Background

## Applications

* Image enhancement
* Image segmentation
* Medical image processing
* Object detection and visualization
* Computer Vision laboratory experiments

## Repository Contents

* `README.md` – Project documentation
* `.ipynb` – Python implementation of image slicing

## Author

Computer Vision Lab Project

<img width="1189" height="887" alt="image" src="https://github.com/user-attachments/assets/c600ebe1-71a9-4d3d-b3d6-c05b636696b7" />

