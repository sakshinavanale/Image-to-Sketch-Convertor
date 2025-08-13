# 🖼️ Image Converter Tools with Python

This repository contains two simple GUI-based image processing tools built with **Python**, **OpenCV**, and **Tkinter**:

- 🎨 **Grayscale Image Converter**  
- ✏️ **Pencil Sketch Converter**

These projects are ideal for beginners looking to explore **basic computer vision** and **GUI development**.

---

## 📁 Projects Overview

### 1. 🎨 Grayscale Image Converter

A GUI application to convert any image to grayscale using OpenCV.

**Features:**
- Simple UI with Tkinter
- Supports common image formats (.jpg, .png, .bmp, .tiff)
- Converts and displays grayscale image using OpenCV window

**Run with:**
```bash
python grayscale_converter.py


### 2. ✏️ Pencil Sketch Converter

A GUI application that transforms your image into a pencil sketch using basic image processing techniques.

**Features:**
- Side-by-side preview of original and sketch image using Tkinter
- Uses OpenCV functions like:
  - `cv2.cvtColor()` for grayscale conversion
  - `cv2.bitwise_not()` for image inversion
  - `cv2.GaussianBlur()` for smoothing
  - `cv2.divide()` to create the sketch effect
- Option to save the sketch image in PNG format

**Run with:**
```bash
python image_sketch.py
