# 🏋️‍♂️ AI Fitness Form Tracker  

**AI Fitness Form Tracker** is an intelligent pose estimation project built using **Python**, **OpenCV**, and **MediaPipe**.  
It detects body landmarks from a video or webcam feed and calculates joint angles (like arm bend angles) in real time.  
The project visually displays progress as a percentage bar, helping users monitor their workout form and movement range.  

## 🎯 **Project Objective**
The main goal of this project is to track and analyze human body movements during exercises using AI.  
It helps identify how well the user performs an action (like a bicep curl) by calculating joint angles and displaying progress visually on screen.

## ⚙️ **Technologies Used**
- **Python 3.x**
- **OpenCV** – for image and video processing  
- **MediaPipe** – for real-time pose detection and landmark tracking  
- **NumPy** – for mathematical operations  
- **Math & Time** libraries – for angle calculation and frame timing
- 
## 🧩 **Features**
✅ Detects full-body landmarks using MediaPipe Pose  
✅ Calculates arm joint angles in real time  
✅ Displays progress percentage visually using a dynamic bar  
✅ Shows FPS for performance monitoring  
✅ Can be used for fitness tracking, yoga pose correction, or gesture analysis  

## 🚀 **How to Run**

1️⃣ Install Dependencies
Make sure Python 3.7+ is installed, then run:
pip install opencv-python mediapipe numpy

2️⃣ Add Your Video

Place your input video in the project folder (e.g., 8.mp4) or use a webcam feed by changing:

cap = cv2.VideoCapture(0)

3️⃣ Run the Project
python pose_tracker.py


Press Q to quit the window.
