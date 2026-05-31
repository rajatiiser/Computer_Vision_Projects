# Advanced Image Processing Techniques for Computer Vision

## Overview

This project demonstrates the implementation of advanced classical image processing techniques for computer vision without using deep learning architectures. The objective is to explore how traditional computer vision methods can be applied for object detection, image alignment, geometric transformations, and image stitching.

The project was developed as part of a mini-project on Advanced Image Processing Techniques for Computer Vision.

## Techniques Implemented

### 1. Object Detection using Haar Cascade Classifiers

* Face detection on the astronaut image.
* Eye detection within the detected face region.
* Detection parameters were tuned to reduce false positives.
* Circular annotations and labels were used for improved visualization.

### 2. Image Alignment using ORB Feature Matching

* ORB (Oriented FAST and Rotated BRIEF) feature detector was used.
* A shifted version of the rocket image was generated.
* Feature correspondences were established using Brute Force Matching.
* Matched keypoints demonstrate successful image alignment.

### 3. Transformation Models (Affine Transformation)

* Affine transformation was applied to the text image.
* Demonstrated geometric operations including translation, scaling, and rotation.
* Visual comparison between original and transformed images was performed.

### 4. Image Stitching

* The coffee image was divided into two overlapping regions.
* Left and right sections were stitched together using horizontal concatenation.
* The reconstructed image closely matched the original image.
* Demonstrated the basic principle of panorama creation and image reconstruction.

## Dataset

All images were obtained from the built-in `skimage.data` library:

* Astronaut
* Rocket
* Text
* Coffee

No external datasets or image downloads were used.

## Libraries Used

* Python
* OpenCV
* NumPy
* Matplotlib
* scikit-image

## Results

The project successfully demonstrated:

* Accurate face and eye detection using Haar Cascade classifiers.
* Robust feature matching using ORB descriptors.
* Geometric image transformations using affine models.
* Reconstruction of images through stitching techniques.

These classical computer vision techniques provide the foundation for many modern image analysis systems.

## How to Run

1. Clone the repository.

```bash
git clone https://github.com/yourusername/Advanced_Image_Processing.git
```

2. Install required libraries.

```bash
pip install -r requirements.txt
```

3. Open the notebook.

```bash
jupyter notebook Advanced_Image_Processing.ipynb
```

4. Run all cells sequentially.

## Author

Rajat Kumar
Professional  Master in Data Science and AI
Master in  Mathematics
