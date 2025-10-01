# AI Squat Tracker (Capstone Project)

Senior capstone project at CU Boulder.  
Real-time squat tracking system using computer vision + machine learning.  
The goal: give live feedback on squat form to improve safety and performance.

---

## 🚀 Features
- Real-time pose detection with **MediaPipe** + **OpenCV**
- **FastAPI** backend with health check endpoint
- Live webcam demo for pose landmark tracking
- Model training with **YOLOv8** for barbell detection and rep analysis
- Visualized training metrics (loss curves, precision, recall, mAP)

---

## 📊 Training Results
Example from our first trained YOLOv8 model:

![Training Results](assets/modelV1_Curves.png)

---

## 📂 Repo Structure
- `main.py` → FastAPI server with health check
- `pose_webcam_demo.py` → Live demo with MediaPipe + OpenCV
- `test_imports.py` → Verifies dependencies are installed correctly
- `requirements.txt` → Environment setup
- `/notebooks` → Model training and analysis
- `/results` → Training outputs + metrics
- `/assets` → Images and plots

---

## ⚡ Quickstart
```bash
# clone the repo
git clone https://github.com/matthewcicero/ai-computer-vision-squat-tracker.git
cd ai-computer-vision-squat-tracker

# install dependencies
pip install -r requirements.txt

# run a quick demo
python pose_webcam_demo.py
