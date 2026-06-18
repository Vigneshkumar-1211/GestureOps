<div align="center">

# 🖐️ GestureOps

**Control your system with hand gestures — no mouse, no keyboard.**

[![Python](https://img.shields.io/badge/Python-3.8%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand%20Tracking-0097A7?style=for-the-badge&logo=google&logoColor=white)](https://mediapipe.dev/)
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey?style=for-the-badge)]()
[![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)]()

</div>

---

## 🏗️ Architecture

![GestureOps Architecture](image.png)

---

## 📌 Overview

**GestureOps** is a real-time hand gesture recognition system built in Python that maps hand gestures captured via webcam to system-level operations. Leveraging **MediaPipe** for landmark detection and **OpenCV** for frame processing, GestureOps enables touchless interaction with your computer — ideal for accessibility use cases, presentations, smart environments, and HCI research.

---

## ✨ Features

- 🎯 **Real-time gesture detection** via webcam using MediaPipe Hand Landmarks
- 🖱️ **System control** — mouse movement, clicks, scrolling, and keyboard shortcuts triggered by gestures
- 🔄 **Live video feedback** with hand landmark overlay rendered using OpenCV
- ⚙️ **Modular and extensible** — easily add new gesture-to-action mappings
- 🪶 **Lightweight** — runs on standard consumer hardware without a GPU

---

## 🛠️ Tech Stack

| Component | Library / Tool |
|---|---|
| Hand Landmark Detection | [MediaPipe](https://mediapipe.dev/) |
| Camera & Frame Processing | [OpenCV](https://opencv.org/) |
| Mouse & Keyboard Control | [PyAutoGUI](https://pyautogui.readthedocs.io/) |
| Language | Python 3.8+ |

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/Vigneshkumar-1211/GestureOps.git
cd GestureOps
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate        # macOS / Linux
venv\Scripts\activate           # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

> **Note:** If a `requirements.txt` is not present, install the core dependencies manually:
> ```bash
> pip install mediapipe opencv-python pyautogui
> ```

---

## 🚀 Usage

```bash
cd GestureOps
python gesture_ops.py
```

- Allow webcam access when prompted.
- Position your hand clearly in the camera frame.
- Perform the supported gestures to trigger the corresponding system actions.
- Press `Q` to quit.

---

## 🤚 Supported Gestures

> *(Update this table to match the gestures implemented in your project.)*

| Gesture | Action |
|---|---|
| ☝️ Index finger up | Move cursor |
| 🤏 Pinch (thumb + index) | Left click |
| ✌️ Two fingers up | Right click |
| ✋ Open palm | Scroll |
| 👊 Closed fist | Stop / Pause |
| 👍 Thumbs up | Volume up |
| 👎 Thumbs down | Volume down |

---

## 📋 Prerequisites

- Python **3.8** or higher
- A functioning **webcam**
- Adequate **lighting** for reliable hand detection

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "feat: add your feature"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

Please follow consistent code style and add comments where appropriate.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Vigneshkumar**
- GitHub: [@Vigneshkumar-1211](https://github.com/Vigneshkumar-1211)

---

<div align="center">

*Built with Python, MediaPipe, and OpenCV.*

⭐ **Star this repo if you found it useful!**

</div>
