<h1 align="center">🖐️ Hand Gesture Volume Control 🎵</h1>
<p align="center">
  <b>A Python project that uses OpenCV and MediaPipe to recognize hand gestures in real time and control the system volume.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/OpenCV-4.x-green.svg" alt="OpenCV Version">
  <img src="https://img.shields.io/badge/MediaPipe-Latest-orange.svg" alt="MediaPipe">
  <img src="https://img.shields.io/github/license/hiu154/hand-gesture-volume-control" alt="License">
</p>

---

### 🧠 Overview
This project allows you to **control your system's volume using hand gestures** captured through your webcam.  
By tracking your hand in real-time using **OpenCV** and **MediaPipe**, the program adjusts the volume based on the **distance between your thumb and index finger**.

Perfect for:
- 🎮 Automation projects  
- 🧑‍🦽 Accessibility and hands-free control  
- 🧪 Computer vision & AI experimentation  

---

### ⚙️ Features
✅ Real-time hand tracking using **MediaPipe Hands**  
✅ Smooth and responsive **gesture-to-volume mapping**  
✅ Works on **Windows, macOS, and Linux**  
✅ Adjustable sensitivity and detection accuracy  
✅ Simple and clean UI feedback (volume bar, FPS display)  

---

### 🛠️ Tech Stack
- **Python 3.8+**
- **OpenCV** – Video capture & visualization  
- **MediaPipe** – Hand tracking  
- **PyCaw** (Windows) – Volume control API  
- **Numpy** – Math operations  

---

### 🚀 Installation
```bash
# Clone the repository
git clone https://github.com/hiu154/hand-gesture-volume-control.git
cd hand-gesture-volume-control

# Install dependencies
pip install -r requirements.txt
