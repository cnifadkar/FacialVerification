# Facial Verification

![Project Banner](path/to/your/banner/image.jpg)

## Overview

This project implements a facial verification system using a Siamese neural network architecture built with TensorFlow and Keras. The model is designed to perform real-time facial verification by comparing input images against a set of known images, achieving high precision and recall. The system is capable of verifying identities with a custom threshold-based approach and is designed for use in various applications, from personal authentication to more secure environments.

## Features

- **Siamese Neural Network**: A custom Siamese network with an L1 distance layer for comparing image embeddings.
- **Real-Time Verification**: Integration with OpenCV to capture images from a webcam and perform real-time facial verification.
- **High Accuracy**: The model was trained to achieve high precision and recall on test data, with a verification success rate of 64% in real-time testing.
- **Customizable Thresholds**: Fine-tune detection and verification thresholds to balance accuracy and false positive/negative rates.
- **Model Persistence**: Save and load trained models for future use.

## Project Structure

