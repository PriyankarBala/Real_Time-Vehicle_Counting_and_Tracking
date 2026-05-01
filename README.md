# 🚗 Real-Time Vehicle Detection, Tracking & Counting using YOLO

## 📌 Overview

This project implements a **real-time vehicle detection, tracking, and counting system** using the **Ultralytics YOLO model** and **OpenCV**. It processes video input, detects vehicles, tracks them across frames, and counts objects crossing a defined line.

---

## 🎥 Demo Preview

![Demo](demo.gif)

---

## 🎯 Features

* 🚘 Vehicle detection using YOLO
* 🎯 Object tracking with unique IDs
* 📊 Vehicle counting based on line crossing
* 📹 Works with video files or live camera
* ⚡ Optimized for real-time performance
* 🖥️ GPU acceleration support (CUDA)

---

## 🛠️ Tech Stack

* **Python 3.11**
* **Ultralytics YOLO**
* **OpenCV (cv2)**
* **NumPy**
* **PyTorch (CUDA enabled for GPU)**

---

## 📂 Project Structure

```
demo_detect_track_count_multiple_vehicles/
│
├── test_videos/              # Input videos (ignored in Git)
├── Track&Count.ipynb         # Main notebook
├── .gitignore
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/PriyankarBala/Real_Time-Vehicle_Counting_and_Tracking.git
cd Real_Time-Vehicle_Counting_and_Tracking
```

### 2️⃣ Create virtual environment

```bash
python -m venv .venv
```

Activate it:

**Windows (PowerShell):**

```bash
.\.venv\Scripts\activate
```

### 3️⃣ Install dependencies

---

## 🧠 Model

This project uses **Ultralytics YOLO models**.

👉 Download models automatically or from:
https://github.com/ultralytics/assets

---

## 🚀 Usage

### ▶️ Run using Python script

```bash
python main.py
```

### ▶️ Or run in Jupyter Notebook

Open:

```
Track&Count.ipynb
```

---

## 🎥 Demo Video

## Watch demo here:
https://drive.google.com/file/d/1B1AAZV0TU9mFoeMJeZrQheDY237DNgco/view?usp=sharing

---

## 📂Test Videos

You can try with other videos as well. The video files are given below:
https://drive.google.com/drive/folders/1Q4D0qTKO4ImX7mZF3LZAX2VjY6Fjv7jq?usp=sharing

---

## 📊 Output

* Bounding boxes around detected vehicles
* Unique ID tracking
* Count display on screen
* Line crossing detection

---

## 🧪 Requirements

* ultralytics
* opencv-python
* numpy
* torch
* torchvision
* torchaudio

---

## 💡 Future Improvements

* Speed estimation of vehicles
* Multi-lane detection
* Traffic density analysis
* Web dashboard integration

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

---
