# Sign Language Detection using Action Recognition with Python

This project is a deep learning-based solution for sign language detection using action recognition. It leverages a keypoint detection model to create a sequence of keypoints, which are then passed to an action detection model powered by LSTM layers. This allows for the real-time prediction of sign language in video sequences.

## Key Features

- **Extract MediaPipe Holistic Keypoints:** The project extracts keypoints using MediaPipe Holistic, capturing body, face, and hand landmarks.

- **LSTM-based Action Detection:** Sign language recognition is achieved through action detection powered by LSTM layers. This allows the model to understand and interpret the sequence of keypoints over time.

- **Real-time Prediction:** The model can be used to predict sign language gestures in real-time from video sequences.

## Requirements

- Python
- TensorFlow
- Keras
- MediaPipe


## Usage

1. Start the application, which will use your computer's webcam to capture video input.

2. The project will use MediaPipe to detect holistic keypoints in the video stream.

3. The LSTM-based action recognition model will analyze the sequence of keypoints to predict sign language gestures in real-time.

4. The predicted sign language gestures will be displayed or can be used for further actions, such as controlling a sign language interpreter or a sign-to-text translation system.

## Acknowledgments

- The project utilizes the [MediaPipe](https://mediapipe.dev/) library for keypoint detection.

- Deep learning models are built using [TensorFlow](https://www.tensorflow.org/) and [Keras](https://keras.io/).




