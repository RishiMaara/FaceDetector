🛠️ Internship Note
This project was developed as part of our 15-day internship at PC World, where we applied computer vision techniques to build a real-time facial landmark detection system using Python.

# 🎯 Face Landmark Detector using Python & OpenCV

This project is a **real-time Face Landmark Detection** system built using **Python**, **OpenCV**, and **Dlib**. It detects key facial landmarks such as eyes, nose, lips, and jawline from both images and live video feeds, enabling precise facial analysis for further applications like emotion recognition, face alignment, or AR filters.

## 🔍 Features

* ✅ Real-time face and facial landmark detection using webcam
* ✅ Supports 68-point landmark model (eyes, eyebrows, nose, lips, chin)
* ✅ Processes images and video streams
* ✅ Lightweight and efficient Python implementation
* ✅ Easily extendable for emotion detection, head pose estimation, and more

## 🧠 Tech Stack

* Python 3.x
* OpenCV
* Dlib (pre-trained 68 facial landmark predictor)
* NumPy

## 📸 How it Works

1. Detect faces in the input image/frame using Dlib’s frontal face detector
2. Apply the 68-point shape predictor to extract facial landmarks
3. Draw landmark points as overlays on the face
4. Display the result in real-time

## 🚀 Getting Started

```bash
pip install opencv-python dlib numpy
python face_landmark_detector.py
```

## 📁 Files

* `face_landmark_detector.py` – main Python script
* `shape_predictor_68_face_landmarks.dat` – pretrained landmark model
* `README.md` – project overview and instructions

## 🤖 Use Cases

* Emotion detection
* Face alignment
* Virtual makeup / filters
* Face-based authentication systems

## 📌 License

MIT License

---

Let me know if you'd like a README.md file version ready to upload.
