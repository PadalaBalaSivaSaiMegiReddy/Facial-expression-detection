# Emotion Detection using Facial Detection Android App

This is an Android application developed using Android Studio that detects emotions from facial expressions in real-time. The app uses a Convolutional Neural Network (CNN) model written in Python for emotion detection and Firebase for the login page.

## Features

The app has the following features:
* Real-time facial detection using the device's camera
* Emotion detection from facial expressions (happy, sad, angry, surprised, neutral)
* Firebase authentication for user login

## Requirements

To run the app, you will need:
* Android Studio 3.0 or later
* An Android device or emulator running Android 4.4 KitKat or later
* Python 3.6 or later
* Keras 2.2.4 or later
* TensorFlow 1.13.1 or later
* OpenCV 3.4.3 or later
* Firebase account for authentication

## Installation

1. Clone this repository using Git or download the ZIP file.
2. Import the project into Android Studio.
3. Install the required dependencies for the Python model (Keras, TensorFlow, OpenCV).
4. Run the Python script `emotion_detection.py` to train the model.
5. Export the trained model to a TensorFlow Lite file using the script `export_tflite.py`.
6. Copy the TensorFlow Lite file to the `assets` folder in the Android project.
7. Configure Firebase for authentication.
8. Run the app on an Android device or emulator.

## Usage

1. Launch the app on an Android device or emulator.
2. Sign in using your Firebase credentials.
3. Grant the app permission to access the device's camera.
4. Point the camera at your face.
5. The app will detect your facial expression and display your emotion on the screen.

## Credits

This project was developed by Bala Siva Sai Megi Reddy Padala as part of Intelligent Model Design Course at Bennett University.
 <!-- The emotion detection model was adapted from the work of [Name et al.] and the code was modified from [Source] under the [License]. -->
