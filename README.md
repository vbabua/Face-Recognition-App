# Siamese Network for Face Verification

This repository contains code for a face verification system based on a Siamese Network model. It includes a Kivy-based GUI application to interact with a webcam feed and perform real-time face verification.

## Overview
The system captures frames from a webcam feed, applies pre-processing, and uses a trained Siamese Network model for face verification. If the captured face matches with any of the verified faces stored in the system, it is identified as "Verified". If not, it is identified as "Unverified".

## Files
Siamese Network for Face Verification.ipynb: This is a Jupyter Notebook file containing code to train a Siamese Network for face verification. It also demonstrates how to test the trained model.
faceid.py: This is a Python script that builds a Kivy application for real-time face verification. It captures frames from a webcam feed, preprocesses the frames, and passes them through the trained Siamese Network model for verification.
layers.py: This is a Python script that contains a custom TensorFlow layer for computing the L1 distance. This layer is used in the Siamese Network model.

## Prerequisites
Python 3.7 or later.
TensorFlow 2.5.0 or later.
Kivy 2.0.0 or later.
OpenCV 4.5.2 or later.
NumPy.

## Installation
1. Clone the repository:
  git clone git-repository-url
2. Navigate to the cloned directory:
  cd siamese-face-verification
3. Install the required packages:
  pip install -r requirements.txt

## Usage
Train the Siamese Network model using the provided Jupyter Notebook.
Run the Kivy application for real-time face verification:
python faceid.py

## Limitations
The current version of this system uses a simple thresholding method for face verification, which might not perform well in complex scenarios. Future improvements may include advanced feature extraction and comparison methods for more accurate face verification.


