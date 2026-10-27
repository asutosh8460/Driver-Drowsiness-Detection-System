<div align="center">

# 😴 Driver Drowsiness Detection System

### Real-time detection of driver fatigue from a webcam feed, with an instant audio alert

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Status](https://img.shields.io/badge/Status-Working-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

</div>

---

## 📌 Overview

Drowsy driving is a major cause of road accidents. This project watches the driver through a webcam, tracks the eyes frame by frame, and raises an alarm when signs of drowsiness appear, such as eyes staying closed for too long.

> **[Replace this line with one sentence on your approach, e.g. "It uses facial landmarks to compute the Eye Aspect Ratio (EAR) and triggers an alert when EAR stays below a threshold."]**

## 🎬 Demo

<!-- Add a GIF or screenshots to a /assets folder, then update the paths below -->
<div align="center">

![Demo](assets/demo.gif)

| Alert state | Normal state |
|:-----------:|:------------:|
| ![Drowsy](assets/drowsy.png) | ![Alert](assets/alert.png) |

</div>

## ✨ Features

- 🎥 **Real-time detection** from a live webcam stream
- 👁️ **Eye-state tracking** across consecutive frames
- 🔔 **Instant alert** when drowsiness is detected
- ⚡ **Lightweight**, runs on a regular laptop with no special hardware
- 🧩 **[Add any other feature, e.g. yawn detection, adjustable threshold]**

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Computer Vision | OpenCV |
| Detection / Model | **[e.g. dlib, MediaPipe, Haar cascades, CNN (Keras / TensorFlow)]** |
| Libraries | NumPy, **[add others from requirements.txt]** |

## 🧠 How It Works

1. **Capture:** frames are read from the webcam.
2. **Detect:** the face and eyes are located in each frame.
3. **Analyse:** **[explain your method, e.g. EAR is computed, or the CNN classifies the eye as open or closed]**.
4. **Decide:** if the eyes stay closed for more than **[N]** consecutive frames, the driver is flagged as drowsy.
5. **Alert:** an on-screen warning and **[audio alarm]** are triggered.

## 📁 Project Structure

```
Driver-Drowsiness-Detection-System/
├── Driver-Drowsiness-Detector-master 1/   # Project source code
├── assets/                                # Demo GIF and screenshots
├── requirements.txt                       # Dependencies
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
cd Driver-Drowsiness-Detection-System

# 2. (Optional) Create a virtual environment
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # macOS / Linux

# 3. Install dependencies
pip install -r requirements.txt
```

### Run

```bash
python your_main_file.py
```

Press **`q`** to quit the webcam window.

## 📊 Results

| Metric | Value |
|--------|-------|
| Detection accuracy | **[add if measured]** |
| Frame rate | **[e.g. ~20 FPS on CPU]** |

## 🔮 Future Improvements

- [ ] Yawn and head-pose detection for better accuracy
- [ ] Night and low-light support
- [ ] Mobile or in-vehicle embedded deployment
- [ ] Logging and fatigue-trend reports

## 🤝 Contributing

Suggestions and pull requests are welcome. Open an issue to discuss what you would like to change.

## 👤 Author

**Asutosh Khairnar**

[![GitHub](https://img.shields.io/badge/GitHub-asutosh8460-181717?style=flat&logo=github)](https://github.com/asutosh8460)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-asutoshkhairnar-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/asutoshkhairnar)

---

<div align="center">

⭐ If you found this project useful, consider giving it a star.

</div>
