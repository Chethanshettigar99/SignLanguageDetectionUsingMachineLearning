# SignLanguageDetectionUsingMachineLearning

This project is a real-time sign language detection system that uses machine learning to recognize and classify A-Z hand gestures from video feeds. It leverages an LSTM-based neural network model trained on keypoints extracted from video frames to predict and display sign language letters with high accuracy.

Technologies Used: TensorFlow, Mediapipe, OpenCV, Keras, Python.

Model Architecture: The project employs an LSTM-based neural network for sequential prediction of hand gestures, trained on keypoints extracted from video frames.

Real-Time Detection: The system captures video input, processes it to detect hand landmarks, and predicts the corresponding sign language letter using a pre-trained model.

Prediction Visualization: Outputs the predicted sign language gesture on the screen in real-time, with a confidence score displayed alongside.
