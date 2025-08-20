# 👁️ Face-Controlled Mouse Tracker

A real-time computer vision project that uses OpenCV and PyAutoGUI to detect the user's face via webcam and automatically adjust the mouse position if the face moves outside a defined boundary.

---

## 🚀 Features

- Face and eye detection using Haar Cascade classifiers  
- Automatic mouse movement based on face position  
- Visual boundary box to guide user alignment  
- Live webcam feed with annotated overlays

---

## 🛠️ Technologies Used

- Python 3.10  
- OpenCV  
- PyAutoGUI  
- Haar Cascade XML models

---

## 📦 Installation

1. Install required packages:
pip install opencv-python pyautogui matplotlib

2. Download and place the following Haar Cascade files in your project directory:
- haarcascade_frontalface_default.xml
- haarcascade_eye.xml
- 
3. Run the script:
python face_mouse_control.py

```bash
