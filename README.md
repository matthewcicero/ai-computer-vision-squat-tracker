# AI Squat Tracker

Capstone project at CU Boulder. The goal is to provide real-time squat form feedback using computer vision and machine learning.

## Results
Example training run (YOLOv8):
![Training curves](assets/modelV1_Curves.png)

Key metrics:
- Precision: 0.78
- Recall: 0.82
- mAP@50: 0.87
- mAP@50-95: 0.61

## Repo Structure
- `main.py` — FastAPI server with health check
- `pose_webcam_demo.py` — MediaPipe Pose demo using webcam + OpenCV
- `test_imports.py` — simple dependency check
- `requirements.txt` — environment setup

## Quickstart
Clone the repo and install requirements:
```bash
git clone https://github.com/matthewcicero/ai-squat-tracker.git
cd ai-squat-tracker
pip install -r requirements.txt
