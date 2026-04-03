# Low-Light Image Enhancement

## Overview

This project improves the visibility of images captured in low-light conditions. It applies a contrast enhancement technique to make dark images clearer and easier to interpret.

---

## Problem

Images taken in dim environments often appear dark and lack detail, which can affect tasks like monitoring and visual analysis.

---

## Approach

The enhancement process is based on CLAHE (Contrast Limited Adaptive Histogram Equalization):

* Convert image from BGR to LAB color space
* Extract the brightness (L) channel
* Apply CLAHE to enhance contrast
* Merge channels and reconstruct the image

---

## Results

* Increased brightness
* Improved contrast
* Better visibility of details

---

## Tech Stack

* Python
* OpenCV
* NumPy
* Matplotlib

---

## Sample Output

Original vs Enhanced:

