# Virtual Room Try-On for clothes(shirts)

## Overview

This project demonstrates a virtual room try-on feature for clothes (shirts) using computer vision. Using Mediapipe for facial landmark detection and OpenCV for image manipulation, we overlay a shirt on a user's body in real-time via webcam.

## Features

- Real-time face tracking using Mediapipe
- Accurate placement of eyewear based on facial landmarks
- Support for images with transparency (PNG)

## Prerequisites

1. Python 3.x
2. OpenCV
3. Mediapipe

### Installation

Clone this repository and install the dependencies:

```bash
git clone https://github.com/yourusername/virtual-try-on-coolers.git
cd virtual-try-on-coolers
pip install opencv-python mediapipe
