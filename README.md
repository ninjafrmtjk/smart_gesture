# smart_gesture

# 🖐️ Hand Mouse Control

> Control your computer with hand gestures — no mouse needed.

Built with **MediaPipe** + **OpenCV**, this project tracks your hand through a webcam in real time and translates gestures into mouse actions.

---

## ✨ Features

- 🖱️ **Move cursor** — point with your index finger
- 👆 **Single click** — pinch thumb and index finger
- ✌️ **Double click** — pinch twice quickly
- 🖐️ **Scroll** — raise all four fingers, tilt hand up/down
- 📸 **Screenshot** — make a fist

---

## 🚀 Quick Start

```bash
# Create virtual environment with Python 3.11
py -3.11 -m venv venv
venv\Scripts\activate

# Install dependencies
pip install mediapipe==0.10.9 opencv-python pyautogui

# Run
python gesturetest.py
```

> Press **Q** to quit.

---

## 📦 Requirements

- Python 3.11
- Webcam

---

## 📄 License

MIT
