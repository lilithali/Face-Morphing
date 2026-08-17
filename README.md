# Face Morphing

Face morphing using Delaunay triangulation, affine warping, bilinear interpolation, and image blending.

## Overview

This project generates smooth transitions between two face images by aligning corresponding facial landmarks and warping both faces into intermediate shapes.

The morphing pipeline uses Delaunay triangulation to divide the face into triangular regions. Each triangle is transformed using affine warping, and bilinear interpolation is applied to obtain smooth pixel values. The warped images are then blended to generate intermediate frames.

## Methods

- Facial landmark correspondence
- Delaunay triangulation
- Affine transformation
- Inverse warping
- Bilinear interpolation
- Image blending

## Technologies

- Python
- NumPy
- SciPy
- Matplotlib
- OpenCV
- Jupyter Notebook
