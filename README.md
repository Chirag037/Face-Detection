# 🧠 Real-Time Face Detection using OpenCV

A beginner-friendly Python project that uses your webcam and OpenCV to detect faces in real time. Perfect for anyone getting started with computer vision!

---

## 📸 Demo

![Face Detection Demo](https://media.giphy.com/media/l0HlSNOxJB956qwfK/giphy.gif) 

---

## 🚀 Features

- Real-time face detection from webcam
- Uses Haar Cascade Classifier
- Lightweight and easy to understand
- Written in pure Python

---

## 🛠️ Requirements

- Python 3.6 – 3.11 (⚠️ OpenCV does **not** fully support Python 3.13 yet)
- OpenCV
- NumPy

Install dependencies:

```bash
pip install opencv-python
🧾 Usage
Clone the repository:

bash
Copy
Edit
https://github.com/Chirag037/Face-Detection
cd face-detection-opencv
Run the script:

bash
Copy
Edit
python main.py
Press Q to exit the camera view.

🧠 How It Works
Uses OpenCV’s haarcascade_frontalface_default.xml for face detection

Captures frames from webcam using cv2.VideoCapture

Detects and draws green rectangles around faces

📁 Project Structure
pgsql
Copy
Edit
face-detection/
├── main.py
├── README.md
└── haarcascade_frontalface_default.xml  <-- Optional (OpenCV includes it)
