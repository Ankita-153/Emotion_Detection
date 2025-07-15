# Emotion_Detection
 Features
 Multi-Input Support
 Image file
 Video file
 Live webcam

 Face Detection
Uses MediaPipe for fast and accurate face detection.

 Emotion Recognition
Classifies emotions using a pre-trained CNN model (.h5).
for training model  FER2013 dataset is used
80% training data 20% testing data 
 Face Tracking with IDs
 
Uses Dlib correlation tracker to assign a unique ID to each face and track it frame-by-frame.
 Logging to CSV
 All predictions (with timestamp, face ID, frame number, emotion, and confidence) are saved in a CSV file:
emotion_log.csv

Real-time Display
Shows detected faces and emotions with bounding boxes and confidence percentage.
Easy-to-Use Console Menu
Select input type (Image, Video, Webcam) with a simple numbered menu.
video link for demo:-https://drive.google.com/file/d/15wbrEOpLU9WyTmEQJzkiNZ8VErdDPrlT/view?usp=sharing
