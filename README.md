# Image Stitching Project

A Python-based **image stitching** tool that blends overlapping images into a seamless panorama. This project implements key techniques including feature detection, homography estimation, and image blending—powered by OpenCV and NumPy.

##  Features

-Features

Loads multiple images automatically from a folder.

Detects and matches keypoints between overlapping images.

Aligns and blends images into a smooth panorama.

Saves and displays the final stitched result.

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
