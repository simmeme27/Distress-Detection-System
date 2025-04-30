# 🙋‍♀️ AI-Based Distress Detection System (Using OpenCV + MediaPipe)

This is a real-time surveillance system that detects distress signals (both hands raised above head) using a webcam. Once a distress gesture is detected, it automatically sends an alert email to a registered recipient.

## 💻 Tech Stack
- Python
- OpenCV
- MediaPipe
- SMTP (Gmail)
- Email Automation

## 🚨 Features
- Live webcam feed with pose detection
- Hand-above-head gesture detection
- Sends an alert email only once per detection
- Visual alert overlay on screen

## 📸 Screenshot
![sample_output](sample_output.png)

## 🛠️ How to Run
1. Install the required libraries:
```bash
pip install opencv-python mediapipe
