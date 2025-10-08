# REALTIME-AI
# 🎯 Real-Time Object Detection with Voice Feedback (YOLOv8 + Python)

## 📌 Overview

This project combines **Computer Vision** and **Speech Synthesis** to create an AI system that can *see and speak* in real time.
Using **YOLOv8** for object detection and **pyttsx3** for voice output, the program captures live video from your webcam, detects objects, displays them on-screen, and announces what it sees — for example:

> “I can see a person.”

It’s an interactive demonstration of how visual AI can connect with human-like feedback systems.

---

## 🧠 Features

* Real-time object detection using **YOLOv8**
* Automatic voice announcements of detected objects
* Display of bounding boxes and labels on live video feed
* Works **offline** (no internet required for voice)
* Prevents repeated voice output for the same object

---

## 🧩 Technologies Used

* **Python 3.x**
* **Ultralytics YOLOv8** (for AI model inference)
* **OpenCV** (for video capture and visualization)
* **pyttsx3** (for text-to-speech output)

---

## ⚙️ Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/yolo-voice-detection.git
   cd yolo-voice-detection
   ```

2. **Install dependencies**

   ```bash
   pip install ultralytics opencv-python pyttsx3
   ```

3. **Run the program**

   ```bash
   python main.py
   ```

---

## 🧩 How It Works

1. The webcam captures each video frame in real time.
2. YOLOv8 analyzes each frame and identifies all visible objects.
3. The program checks which objects are newly detected.
4. It announces their names using text-to-speech.
5. Bounding boxes and labels appear on the live video window.

---

## 🎯 Use Cases

* Assistive systems for visually impaired users
* Smart surveillance and robotics
* AI learning demos and interactive AI exhibits

---

## 📸 Example Output

```
I can see a person
I can see a bottle
```

(Displayed live with bounding boxes around each detected object.)

---

## 💬 Author

Developed by **Mahmoud Abdelaziz El-Shahat**
🎓 Mechatronics Engineer | AI & Robotics Enthusiast

---

## 🏷️ License

This project is licensed under the **MIT License** — feel free to use, modify, and share.

---

## 🧠 Keywords

`YOLOv8`, `OpenCV`, `Python`, `AI`, `Object Detection`, `Text-to-Speech`, `Real-Time`, `Machine Learning`, `Voice AI`, `Computer Vision`
