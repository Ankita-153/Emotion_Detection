# Emotion Detection System

This project is a real-time **emotion detection system** that uses **MediaPipe** for face detection, **Dlib** for tracking, and a **TensorFlow** `.h5` model for emotion classification. It supports images, video files, and webcam input.

---

## 🎯 Features

- ✅ Detect multiple faces using MediaPipe
- ✅ Assign IDs using Dlib trackers
- ✅ Predict emotion using a trained CNN model (.h5)
- ✅ Show emotion label with confidence
- ✅ Works on:
  - 📷 Images
  - 🎞️ Videos
  - 📹 Live Webcam
- ✅ Logs all emotions to `emotion_log.csv`

---

## 🧠 Emotion Classes

The model predicts one of the following emotions:

'Angry', 'Disgust', 'Fear', 'Happy', 'Sad', 'Surprise', 'Neutral'