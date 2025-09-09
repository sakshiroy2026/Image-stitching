# Image Stitching Project

A Python-based **image stitching** tool that blends overlapping images into a seamless panorama. This project implements key techniques including feature detection, homography estimation, and image blending—powered by OpenCV and NumPy.

##  Features

- Detects and matches key points between images using SIFT (or alternative detectors if needed)
- Estimates projective transformation (homography) via RANSAC
- Warps images into a common frame and merges them into a panorama
- Basic blending to smooth transitions between stitched images
- Modular structure for easy extension of feature detectors, matchers, and blend modes

##  Getting Started

### Prerequisites

- Python 3.x
- OpenCV (`opencv-python`)
- NumPy

You can install dependencies with:

```bash
pip install opencv-python numpy

Image-Stitching/
├── stitch.py         # Main stitching script
├── requirements.txt  # Project dependencies
├── images/           # (Optional) Sample input/output images
└── README.md         # Project overview and usage instructions
