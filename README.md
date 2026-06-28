# 🎯 Facial Emotion Detection System

## 📌 Overview
This project is a real-time facial emotion detection system using Deep Learning and OpenCV. It detects human emotions through webcam input.

---

## 🚀 Features
- Real-time face detection using webcam
- CNN-based emotion recognition model
- Detects emotions like Happy, Sad, Angry, Neutral, Surprise
- Fast and lightweight AI model

---

## 🛠 Tech Stack
Python, TensorFlow, Keras, OpenCV, NumPy

---

## 📂 Project Structure
- detect.py → Real-time detection script  
- train.py → Model training script  
- emotion_model.h5 → Trained CNN model  
- haarcascade_frontalface_default.xml → Face detection file  

---

## ▶️ How to Run

### 1. Install dependencies
pip install -r requirements.txt

### 2. Run project
python detect.py

---

## 🎥 Output
- Opens webcam
- Detects face
- Shows emotion in real-time

---

## 💡 Future Improvements
- Improve model accuracy
- Add more emotion classes
- Deploy as web app using Flask/Streamlit
