# cctv-object-detection-yolov8
YOLOv8-based object detection model trained on a CCTV surveillance dataset using Python and Ultralytics. Includes full training pipeline and inference demo.

# 📷 CCTV Object Detection using YOLOv8

This repository contains code to train a custom object detection model using the YOLOv8 architecture on a CCTV surveillance dataset. The training is done in a Python notebook with support for lightweight models, GPU acceleration, and visualization.

## 🧠 Project Overview

- **Model:** YOLOv8n (Nano version for speed and small memory footprint)
- **Dataset:** CCTV Surveillance Dataset from Kaggle
- **Framework:** Ultralytics YOLOv8 + PyTorch
- **Environment:** Jupyter Notebook
- **Target:** Real-time object detection in surveillance footage

## 📁 Files in this Repository

- `harmts.ipynb` – Main notebook: downloading dataset, configuring model, training, and running inference
- `data.yaml` – Dataset configuration (labels and image paths)
- `requirements.txt` – List of required Python packages

## ⚙️ Requirements

Install dependencies with:

```bash
pip install -r requirements.txt

---

### ✅ `requirements.txt`

```txt
torch
ultralytics
opencv-python
matplotlib
pillow
pyyaml
kagglehub
