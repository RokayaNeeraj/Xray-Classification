# Lung X-Ray Image Classification in Python

This repository provides a Python script for image classification on a dataset of lung mask X-ray images. It aims to assist in developing and training models for identifying lung condition ( Covid, Non-Covid, or Normal).

## Key functionalities:

### Data collection and preprocessing:
- Uploads and extracts data from compressed files.
- Builds a DataFrame with image paths and labels.
- Analyzes data distribution and performs cleaning.
- Resizes, converts, and normalizes images.

### Image augmentation and enhancement:
- Defines functions for data scaling, augmentation, and filtering.
- Visualizes the effects of these techniques on sample images.

### Image filtering, enhancement, and feature extraction:
- Implements functions for applying Gaussian blur and contrast enhancement.
- Demonstrates feature extraction using SIFT (optional).
- Visualizes extracted features alongside the original image.

### Data splitting:
- Splits data into training, validation, and test sets.

### Image data augmentation (demonstration):
- Defines an ImageDataGenerator for data augmentation techniques.
- Augments and saves sample images for visualization.

### Data loading and combining (partial):
- Loads original images and labels.

## Requirements:

- Python 3.x
- TensorFlow/Keras
- scikit-learn
- OpenCV (optional)

## Getting Started:

1. Clone this repository.
2. Install the required libraries.
3. Replace the placeholder in load_data.py for loading augmented data.
4. Complete the data combining logic (marked as X) in load_data.py.
5. Modify the script parameters (e.g., data paths, model architecture) as needed.
6. Run the script to preprocess, augment, split, and load your data.

## Further Exploration:

- Experiment with different data augmentation techniques and feature extraction methods.
- Implement and train a machine learning model for lung X-ray classification.
- Explore advanced image segmentation and analysis techniques for medical imaging.

## Disclaimer:

This code is for educational purposes only and should not be used for medical diagnosis. It is crucial to consult with a healthcare professional for any medical concerns.
