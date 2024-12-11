# Gesture Recognition using MediaPipe and OpenCV

This project recognizes hand gestures of a person in real-time, such as "Happy", "Sad", "Ciao/Hi", and "Spiderman". The model is trained using data captured from live gestures and then used to predict the gestures in real-time using a webcam. The recognition is powered by **MediaPipe** and **OpenCV** for pose, face, and hand landmark detection.

## Introduction

The goal of this project is to build a real-time hand gesture recognition system. The system captures the user's gestures, processes the data using **MediaPipe**'s holistic model, and predicts the gesture using a trained machine learning model.

The following gestures are recognized:
- **Happy**
- **Sad**
- **Ciao/Hi**
- **Spiderman**

The system uses a webcam to capture live video frames, which are processed to detect key hand, face, and body landmarks. The data from these landmarks are then used to make predictions about the user's gesture.

## Technologies Used

- **Python**: The programming language used to implement the gesture recognition system.
- **OpenCV**: Open source computer vision library for capturing video frames and image processing.
- **MediaPipe**: A framework by Google for building multimodal applied ML pipelines, which is used here for detecting hand, face, and body landmarks.
- **Scikit-learn**: A machine learning library for training the recognition model.
- **Pandas**: Used to manage and process data for model training.
