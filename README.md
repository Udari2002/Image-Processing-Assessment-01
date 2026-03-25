# Image Processing and Computer Vision - Assessment 01
### University of Ruhuna | Department of Electrical and Information Engineering

This repository contains the implementation for **Assessment 01** of the **EE7204 / EC7205** course. The project explores fundamental image processing techniques, medical image enhancement, and a classical (non-AI) approach to fundus image segmentation.

## 🚀 Project Overview

The assessment is divided into two main components:
1. [cite_start]**Preliminary Work:** Implementation of spatial filters, image pyramids, wavelet-based watermarking, and morphological analysis[cite: 13, 21].
2. [cite_start]**Practical Work:** Designing a student-defined, logical pipeline to segment the Optic Disc from fundus images without using AI/ML[cite: 81, 102].

## 🛠️ Technologies Used
* **Language:** Python
* [cite_start]**Libraries:** OpenCV, NumPy, PyWavelets, Matplotlib [cite: 18, 113]
* [cite_start]**Documentation:** LaTeX [cite: 14]

## 📂 Key Features

### 1. Preliminary Work (Questions 01 - 10)
* [cite_start]**Spatial Filtering:** Average, Median, and Gaussian filtering with various kernel sizes[cite: 27, 36, 40].
* [cite_start]**Image Pyramids:** Generation of 3-level Gaussian and Laplacian pyramids[cite: 45].
* [cite_start]**Digital Watermarking:** Embedding and extracting watermarks using Discrete Wavelet Transform (DWT)[cite: 62].
* [cite_start]**Medical Image Analysis:** * Intensity-based organ segmentation from CT scans[cite: 64].
    * [cite_start]MRI enhancement using histogram equalization and contrast stretching[cite: 70].
* [cite_start]**Morphological Analysis:** Feature extraction (area, perimeter) using erosion, dilation, opening, and closing[cite: 76, 80].

### 2. Practical Work: Fundus Image Segmentation
[cite_start]A classical image processing pipeline designed to isolate the **Optic Disc**[cite: 96, 106]:
* [cite_start]**Pipeline:** Green channel extraction -> Gaussian smoothing -> Global thresholding -> Morphological closing -> Connected Component Analysis [cite: 97-101].
* [cite_start]**Validation:** Performance evaluated on a 50-image subset using pixel-wise overlap metrics[cite: 93, 108]:
    * [cite_start]**Dice Similarity Coefficient (DSC)** [cite: 119, 121]
    * [cite_start]**Jaccard Index (IoU)** [cite: 124, 126]

## 📁 Repository Structure
```text
├── Preliminary_Work/
│   ├── EG2022XXXX_Question_01.py
│   ├── ...
│   └── EG2022XXXX_Question_10.py
├── Practical_Work/
│   └── Index_code_Assessment_01.py
├── Report/
│   └── Index_report_Assessment_01.pdf
└── README.md
