# Fire-Detection-model
A real-time fire detection system using YOLO and OpenCV.
# 🔥 Fire Detection Model

A real-time **Fire Detection System** built using **YOLOv8** and **Ultralytics**, capable of identifying fire from images or video streams. This project is trained on a custom dataset and demonstrates high accuracy in detecting fire hazards using computer vision and deep learning.

---

## 🚀 Features

- Real-time fire detection using YOLOv8
- Custom dataset training and evaluation
- High accuracy on real-world fire scenarios
- Visualization of model performance (Precision, Recall, F1-score curves)
- Easy deployment for CCTV or camera-based systems

---

## 🧠 Model Overview

This project uses **Ultralytics YOLOv8**, a state-of-the-art object detection model.

### Training Configuration:
- **Model:** `yolov8n.pt` (Nano variant for faster performance)
- **Dataset:** Custom dataset defined in `data.yaml`
- **Epochs:** 15
- **Image Size:** 640x640

### Example Command Used:
```bash
yolo task=detect mode=train model=yolov8n.pt data="/content/drive/MyDrive/data/data.yaml" epochs=15 imgsz=640
