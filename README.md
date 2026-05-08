# Image Preprocessor App

Live Demo: https://image-preproceappr-app-a7q5jjwpwedqptw7zbj3ra.streamlit.app/

## Overview

Image Preprocessor App is an advanced image editing and preprocessing web application built using Streamlit, Pillow, OpenCV, NumPy, and Matplotlib.

The application allows users to upload images, apply multiple preprocessing techniques, visualize transformations in real time, and download the processed image.

---

# Features

## Image Upload
- Supports JPG, JPEG, PNG, BMP, TIFF, and WEBP formats

## Resize
- Custom width and height resizing
- High-quality Lanczos interpolation

## Color Processing
- Original mode
- Grayscale conversion
- RGB conversion
- RGBA conversion

## Transformations
- Rotation
- Horizontal flip
- Vertical flip

## Image Enhancements
- Brightness adjustment
- Contrast adjustment
- Saturation control
- Sharpness enhancement

## Filters
- Gaussian Blur
- Sharpen
- Edge Enhance
- Emboss
- Contour
- Median Filter

## Advanced Image Processing
- Min-Max Normalization
- Histogram Equalization
- Canny Edge Detection
- Binary Thresholding
- Otsu Thresholding
- Adaptive Thresholding

## Crop and Padding
- Percentage-based cropping
- Custom padding size and color

## Visualization and Statistics
- Original vs Processed image comparison
- Pixel intensity histogram
- Pixel statistics:
  - Min
  - Max
  - Mean
  - Standard Deviation
  - Mode

## Download Support
Export processed images in:
- PNG
- JPEG
- WEBP

---

# Technologies Used

- Python
- Streamlit
- Pillow
- OpenCV
- NumPy
- Matplotlib

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv env
env\Scripts\activate
```

### Linux / Mac

```bash
python3 -m venv env
source env/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Requirements

Create a `requirements.txt` file and add:

```txt
streamlit
pillow
numpy
opencv-python-headless
matplotlib
```

---

# Run the Application

```bash
streamlit run app.py
```

Application will run at:

```txt
http://localhost:8501
```

---

# Project Structure

```txt
Image-Preprocessor/
│
├── app.py
├── requirements.txt
├── README.md
└── screenshots/
```

---

# Deployment

This application is deployed using Streamlit Community Cloud.

Deployment Link:  

https://image-preproceappr-app-a7q5jjwpwedqptw7zbj3ra.streamlit.app/
---

# Screenshots

<img width="1849" height="841" alt="image" src="https://github.com/user-attachments/assets/892f44fe-d507-449a-b9bd-672a5eaf7133" />


# Use Cases

- Machine Learning preprocessing
- Computer Vision projects
- Dataset preparation
- Edge detection experiments
- Thresholding analysis
- Educational purposes
- Image enhancement workflows



