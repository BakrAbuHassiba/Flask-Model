# 🍱 GetFit - Food Detection API

This is a Flask-based API that uses a YOLOv8 model to detect and classify food items from uploaded images. It is part of the **GetFit** project for recognizing and identifying different dishes using computer vision.

---

## 🚀 Features

- Upload an image and receive detected food items
- YOLOv8 model for fast and accurate image inference
- CORS enabled for frontend integration
- Classifies over **180+ food types**
- Returns predictions with:
  - Bounding box (x, y, width, height)
  - Confidence score
  - Class label

---

## 🛠️ Tech Stack

- Python
- Flask
- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- PIL (Pillow)
- Flask-CORS

---

## 📦 Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/BakrAbuHassiba/GetFit.git
cd GetFit
