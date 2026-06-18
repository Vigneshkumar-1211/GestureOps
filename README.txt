# 🖐️ GestureOps

**Control your computer using hand gestures — no mouse, no keyboard.**

GestureOps is a real-time hand gesture recognition system built with Python, MediaPipe, and OpenCV. It detects hand movements through a webcam and translates them into system actions such as cursor control, clicking, scrolling, and volume adjustment.

---

## 🚀 Features

* Real-time hand tracking using MediaPipe
* Cursor movement with hand gestures
* Gesture-based mouse clicks and scrolling
* Volume control through hand signs
* Live visual feedback with hand landmark detection
* Lightweight and easy to extend

---

## 🏗️ Architecture

![GestureOps Architecture](image.png)

---

## 🛠️ Tech Stack

| Technology | Purpose                            |
| ---------- | ---------------------------------- |
| Python     | Core programming language          |
| MediaPipe  | Hand landmark detection            |
| OpenCV     | Video capture and frame processing |
| PyAutoGUI  | Mouse and keyboard automation      |

---

## 📁 Project Structure

```text
GestureOps/
├── gesture_ops.py
├── requirements.txt
├── README.md
├── LICENSE
└── image.png
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/Vigneshkumar-1211/GestureOps.git
cd GestureOps
```

### Create a virtual environment

```bash
python -m venv venv
```

Activate the environment:

**Windows**

```bash
venv\Scripts\activate
```

**macOS / Linux**

```bash
source venv/bin/activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install mediapipe opencv-python pyautogui
```

---

## ▶️ Running the Project

```bash
python gesture_ops.py
```

### Controls

* Allow webcam access when prompted
* Keep your hand visible within the camera frame
* Perform supported gestures to trigger actions
* Press **Q** to exit

---

## 🤚 Supported Gestures

| Gesture            | Action       |
| ------------------ | ------------ |
| ☝️ Index Finger Up | Move Cursor  |
| 🤏 Pinch           | Left Click   |
| ✌️ Two Fingers Up  | Right Click  |
| ✋ Open Palm        | Scroll       |
| 👊 Closed Fist     | Pause / Stop |
| 👍 Thumbs Up       | Volume Up    |
| 👎 Thumbs Down     | Volume Down  |

---

## 📋 Requirements

* Python 3.8+
* Webcam
* Good lighting conditions

---

## 🔮 Future Improvements

* Custom gesture mapping
* Multi-hand support
* Gesture recording and training
* Presentation mode shortcuts
* AI-based gesture classification

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Vigneshkumar**

GitHub: https://github.com/Vigneshkumar-1211

---

⭐ If you found this project useful, consider giving it a star.
