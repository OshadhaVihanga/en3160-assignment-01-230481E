# EN3160 Assignment 1 on Intensity Transformations and Neighborhood Filtering

**Course:** EN3160 — Image Processing and Machine Vision
**Author:** Oshadha Perera (K.W.A.O.V. Perera)
**Index Number:** 230481E
**University of Moratuwa — Department of Electronic and Telecommunication Engineering**

## Overview

This repository contains the implementation and report for Assignment 1, covering intensity transformations, histogram equalization, gamma correction, spatial filtering, image zooming, and image enhancement techniques using Python and OpenCV.

## Contents

- `230481E_assignment01.ipynb` — Jupyter Notebook containing all code, results, and discussion for each question
- `230481E_a01.pdf` — Final report exported from the notebook
- `images/` — Input images used across the assignment
- `.gitignore` — Excludes environment/cache files from version control

## Topics Covered

1. Piecewise-linear intensity transformation
2. Intensity transformation for MRI white/gray matter accentuation
3. Gamma correction on the L plane in Lab color space
4. Vibrance enhancement via saturation plane transformation
5. Histogram equalization (custom implementation)
6. Foreground-only histogram equalization using HSV masking
7. Sobel filtering (filter2D, manual convolution, and separable kernels)
8. Image zooming — nearest-neighbor and bilinear interpolation, with SSD evaluation
9. Foreground/background segmentation using GrabCut and background blur enhancement
10. Bilateral filtering — OpenCV implementation vs. custom implementation

## Tools and Libraries

- Python 3.11
- OpenCV (`opencv-python`)
- NumPy
- Matplotlib

## How to Run

1. Clone this repository
2. Install dependencies:
