# Facial Recognition Security System for Euromed University

## Project Overview

This project implements a **facial recognition system** using **deep learning** to enhance security at Euromed University. The system allows students to access the university without their ID cards by recognizing their faces through a webcam and identifying them in real time. This project aims to prevent unauthorized access in cases of lost, stolen, or forgotten ID cards.

## Features
- **Real-time Facial Recognition**: Uses deep learning to recognize and verify student faces in real-time.
- **High Accuracy**: Achieved **100% accuracy** during testing.
- **Multiple Person Detection**: The model can detect and recognize multiple faces simultaneously.
- **Security Enhancement**: Adds an additional layer of security by detecting imposters attempting to use someone else’s identity.

## Components
- **Data Collection**: 
  - As the first version, we collected facial data from 10 persons, each contributing 300 images, using a webcam. These images were stored in a database for training.
- **Pre-processing**: 
  - Applied **Gaussian filtering** to reduce noise and enhance image quality before training.
- **Model**: 
  - Utilized a **pre-trained AlexNet model**, customized for facial recognition to distinguish between authorized and unauthorized individuals.
- **Webcam Interface**: 
  - The system captures live images for real-time facial recognition.

## Example

![faceDetection](https://github.com/user-attachments/assets/2a3042be-8d8d-411c-903a-870dabb82a4f)


