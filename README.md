<div align="center">

# 😴 Driver Drowsiness Detection System

**Real-time driver fatigue detection from a webcam feed, with an instant alert**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

</div>

---

## 📌 Overview

Drowsy driving is a leading cause of road accidents, and it is hard for a driver to notice their own fatigue in time. This project monitors the driver through a webcam in real time, tracks the state of the eyes frame by frame, and raises an alert when signs of drowsiness are detected, such as the eyes staying closed for too long.

The goal is a simple, low-cost safety aid that runs on an ordinary laptop with no special hardware.

## ✨ Features

- 🎥 Real-time monitoring using a standard webcam
- 👁️ Frame-by-frame eye-state tracking
- 🔔 Immediate alert when drowsiness is detected
- ⚡ Lightweight and runs on a regular CPU
- 🧩 Easy to read, run and extend

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Computer Vision | OpenCV |
| Dependencies | Listed in `requirements.txt` |

## 🧠 How It Works

1. **Capture:** video frames are read from the webcam.
2. **Detect:** the driver's face and eyes are located in each frame.
3. **Monitor:** the state of the eyes is tracked across consecutive frames.
4. **Decide:** if the eyes stay closed longer than normal blinking, the driver is flagged as drowsy.
5. **Alert:** a warning is triggered so the driver can react in time.

## 📁 Project Structure

```
Driver-Drowsiness-Detection-System/
├── Driver-Drowsiness-Detector-master 1/   # Source code and dependencies
├── .gitignore
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Python 3.x
- A working webcam

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/asutosh8460/Driver-Drowsiness-Detection-System.git

# 2. Move into the project folder
cd "Driver-Drowsiness-Detection-System/Driver-Drowsiness-Detector-master 1"

# 3. (Optional) Create and activate a virtual environment
python -m venv venv
venv\Scripts\activate          # Windows
# source venv/bin/activate     # macOS / Linux

# 4. Install the dependencies
pip install -r requirements.txt
```

### Usage

1. Connect a webcam and position it so the driver's face is clearly visible.
2. Run the main Python script from the project folder.
3. The webcam window opens and monitoring starts automatically.

## 🔮 Future Improvements

- Yawn and head-pose detection for better accuracy
- Better performance in low light and with glasses
- Deployment on an embedded or in-vehicle device
- Logging of alerts to track fatigue over a trip

## 👤 Author

**Asutosh Khairnar**

[![GitHub](https://img.shields.io/badge/GitHub-asutosh8460-181717?style=flat&logo=github)](https://github.com/asutosh8460)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-asutoshkhairnar-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/asutoshkhairnar)

---

<div align="center">

⭐ If you found this project useful, consider giving it a star.

</div>
