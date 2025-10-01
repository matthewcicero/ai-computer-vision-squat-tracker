# AI Squat Tracker (Capstone Project)

AI-powered squat tracker built for our senior capstone project at CU Boulder.  
The goal is to provide **real-time form feedback** for compound lifts (starting with squats) using computer vision and machine learning.

## 🚀 Features
- Real-time pose detection using **MediaPipe + OpenCV**
- FastAPI backend with health check endpoint
- Live webcam demo for pose landmark tracking
- In-progress model training (YOLOv8, barbell detection, and rep analysis via Colab)

## 📂 Repo Structure
- `main.py` → FastAPI server with health check
- `pose_webcam_demo.py` → MediaPipe Pose demo using webcam + OpenCV
- `test_imports.py` → quick check that dependencies install and import correctly
- `requirements.txt` → full environment spec for reproducibility

## ⚡ Quickstart
1. Clone the repo  
   ```bash
   git clone https://github.com/matthewcicero/ai-squat-tracker.git
   cd ai-squat-tracker
