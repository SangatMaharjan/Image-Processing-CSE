# Image Conversion and Representation

This repository contains the lab work for **Image Conversion and Representation**, focusing on the fundamental concepts of digital image processing. The objective of this lab is to understand how images are represented digitally and how they can be converted between different formats, color spaces, and representations using image processing techniques.

---

## Objective

- Understand digital image representation.
- Learn different image color models.
- Perform image format conversion.
- Convert color images to grayscale.
- Study binary image representation.
- Explore pixel intensity values and image matrices.

---

## Theory

A digital image is a two-dimensional array of pixels, where each pixel stores intensity or color information. Image representation depends on the number of channels and bits used for each pixel.

### Types of Image Representation

### 1. Binary Image
- Contains only two pixel values: **0 (Black)** and **255 (White)**.
- Each pixel requires only **1 bit**.
- Commonly used in document processing and OCR.

### 2. Grayscale Image
- Contains shades of gray.
- Pixel values range from **0 to 255**.
- Requires **8 bits per pixel**.

### 3. RGB Color Image
- Consists of three channels:
  - Red (R)
  - Green (G)
  - Blue (B)
- Each channel ranges from **0–255**.
- Requires **24 bits per pixel**.

---

## Image Conversion Performed

The following conversions were performed during the lab:

- Color Image → Grayscale
- Grayscale → Binary
- RGB → HSV (if applicable)
- Image Format Conversion (JPG, PNG, BMP, etc.)

---

## Algorithm

1. Read the input image.
2. Display the original image.
3. Convert the image into the required format.
4. Display the converted image.
5. Save the converted image.
6. Compare the original and converted images.

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib

---

## Libraries

```python
import cv2
import numpy as np
import matplotlib.pyplot as plt
```

---

## Sample Operations

- Read an image
- Display an image
- Convert RGB to Grayscale
- Convert Grayscale to Binary
- Save processed image
- Display histogram (optional)

---

## Expected Output

The program should display:

- Original Image
- Grayscale Image
- Binary Image
- Converted Image Format (if applicable)

---

## Learning Outcomes

After completing this lab, students will be able to:

- Understand digital image representation.
- Differentiate between binary, grayscale, and RGB images.
- Convert images between different formats.
- Perform basic image preprocessing.
- Analyze pixel values and image matrices.

---

## Applications

- Medical Imaging
- Computer Vision
- Face Recognition
- Document Processing
- Image Compression
- Machine Learning
- Object Detection

---

## Repository Structure

```
Image-Conversion-and-Representation/
│
├── images/
│   ├── input.jpg
│   ├── grayscale.jpg
│   ├── binary.jpg
│
├── image_conversion.py
├── README.md
└── requirements.txt
```

---

## Conclusion

This lab demonstrates the basics of digital image representation and conversion. By performing different image transformations, students gain practical knowledge of image preprocessing techniques used in computer vision, image analysis, and machine learning applications.

---

## Author

**Name:** Sangat Maharjan  
**Program:** Bachelor in Computer Engineering  
**College:** Cosmos College of Management and Technology  
**University:** Pokhara University
