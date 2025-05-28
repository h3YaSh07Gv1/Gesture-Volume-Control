Gesture Volume Control 🌺🖐️

Control your system volume using hand gestures detected via webcam using OpenCV, MediaPipe, and Pycaw. This project detects the distance between your thumb and index finger and maps it to the system's volume level.

Features

Real-time hand tracking using MediaPipe

Adjust volume by changing the distance between thumb and index finger

Visual volume bar overlay

Displays current volume percentage and FPS

Requirements 📦

Python 3.7+

OpenCV

MediaPipe

Numpy

Pycaw

comtypes

You can install all dependencies using pip:

pip install -r requirements.txt

requirements.txt (example)

opencv-python
mediapipe
numpy
pycaw
comtypes

Installation 🔧

Clone the repository:

git clone https://github.com/yourusername/GestureVolumeControl.git
cd GestureVolumeControl

Install the dependencies:

pip install -r requirements.txt

How to Run ▶️

Make sure you have a working webcam.

Run the main script:

python GestureVolumeControl.py

Move your thumb and index finger closer or farther apart to decrease/increase the volume.

File Structure 📁

GestureVolumeControl/
├── GestureVolumeControl.py   # Main application script
├── HandTrackingMod.py        # Custom hand detection module
├── requirements.txt
└── README.md

Acknowledgements 🙏

MediaPipe by Google

OpenCV

pycaw