# 🎭 Emotion Detection System using Deep Learning

## 📌 About the Project

The **Emotion Detection System** is a Deep Learning-based application that recognizes human facial emotions in real time using a webcam. The project combines **OpenCV** for face detection with a **Convolutional Neural Network (CNN)** model trained to classify facial expressions into seven different emotions.

This project demonstrates the practical application of Computer Vision and Deep Learning for real-time emotion recognition.

---

## 🚀 Features

* 🎥 Real-time emotion detection using webcam
* 😊 Detects seven facial emotions:

  * Happy
  * Sad
  * Angry
  * Fear
  * Surprise
  * Disgust
  * Neutral
* 👤 Face detection using Haar Cascade Classifier
* 🧠 Emotion classification using a trained CNN model
* ⚡ Fast and lightweight prediction

---

## 🧠 Tech Stack

* Python
* TensorFlow
* Keras
* OpenCV
* NumPy
* Haar Cascade Classifier

---
### Note
This project uses a pre-trained CNN model for emotion recognition. The dataset is not included in this repository due to GitHub size limitations.

## 📂 Project Structure

```
Emotion-Detection-System/
│── detect.py
│── train.py
│── emotion_model.h5
│── haarcascade_frontalface_default.xml
│── README.md
```

---

## 📁 Project Files

| File                                  | Description                           |
| ------------------------------------- | ------------------------------------- |
| `detect.py`                           | Runs real-time emotion detection      |
| `train.py`                            | Trains the CNN model                  |
| `emotion_model.h5`                    | Pre-trained emotion recognition model |
| `haarcascade_frontalface_default.xml` | Face detection model                  |

---

## ⚠️ Dataset

The training dataset is **not included** in this repository because of GitHub file size limitations.

The model was trained using a standard facial emotion dataset such as **FER2013**.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/Emotion-Detection-System.git
```

Go to the project folder:

```bash
cd Emotion-Detection-System
```

Install the required libraries:

```bash
pip install tensorflow opencv-python numpy
```

---

## ▶️ Run the Project

Start the emotion detection application:

```bash
python detect.py
```

Your webcam will open, detect faces, and display the predicted emotion in real time.

---

## 📷 Output

The application detects a face from the webcam and displays one of the following emotions:

* 😊 Happy
* 😢 Sad
* 😡 Angry
* 😨 Fear
* 😲 Surprise
* 🤢 Disgust
* 😐 Neutral

---

## 🔮 Future Improvements

* Improve model accuracy
* Support multiple face detection
* Deploy as a Flask web application
* Add Streamlit interface
* Support image and video file input

---

## 👨‍💻 Author

**Anshuman Sahu**

B.Tech – Computer Science & Engineering (Data Science)

Interested in Artificial Intelligence, Machine Learning, Data Analytics, and Web Development.

---

## ⭐ Support

If you found this project useful, please consider giving this repository a **⭐ Star** on GitHub.

Thank you for visiting!
