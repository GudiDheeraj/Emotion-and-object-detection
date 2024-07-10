# Emotion and Object Detection System

This repository contains a Python application for real-time emotion detection, weapon detection, and animal detection using computer vision techniques and deep learning models. It utilizes OpenCV, DeepFace, TensorFlow, and Twilio for various functionalities.

## Features

- **Emotion Detection**: Analyzes the dominant emotion in an image using the DeepFace library.
- **Weapon Detection**: Detects guns, knives, and bats in real-time using Haar cascade classifiers.
- **Animal Detection**: Uses a pre-trained InceptionV3 model to detect various animals in an image.
- **Alert System**: Sends SMS alerts using Twilio when specific conditions (e.g., fear detected, weapon detected) are met.

## Requirements

- Python 3.x
- OpenCV (`opencv-python`)
- TensorFlow (`tensorflow`, `keras`)
- DeepFace (`deepface`)
- Twilio (`twilio`)

## Setup

1. **Clone the repository:**
   ```bash
  (https://github.com/GudiDheeraj/Emotion-and-object-detection.git)
   cd emotion-and-object-detection
   
2. **Install Dependencies**
3. **Download Haar cascade XML files:**
-Download or create Haar cascade XML files for guns, knives, and bats.
-Ensure they are named gun_cascade.xml, knife_cascade.xml, and bat_cascade.xml respectively.
-Place them in the root directory of the repository.
4. **Set up twilio credentials:**
  - Sign up for a Twilio account if you haven't already: Twilio
  - Obtain your Twilio Account SID, Authentication Token, and Twilio phone numbers.
  - Replace placeholders in the code (main.py) with your actual credentials.
5. **Usage:**
   - Ensure your webcam is connected and accessible.
   - Replace placeholder image paths (happy.jpg and your_image.jpg) in main.py with your own image paths.
   - Run the main script:
   - Follow the instructions displayed in the terminal.
   - Press q to quit the camera feed or close the window.
   - Examples
    - Emotion Detection:
    - Weapon Detection:
    - Animal Detection:


Replace placeholders like `your_username`, `path_to_emotion_detection_image.png`, `path_to_weapon_detection_image.png`, and `path_to_animal_detection_image.png` with actual values corresponding to your project files and images. This README.md file structure provides clear instructions, examples, and information necessary for users and contributors to understand and engage with your project effectively.
