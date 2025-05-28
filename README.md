# Gesture Volume Control 🌺✋

Control your system volume using hand gestures detected via webcam using OpenCV, MediaPipe, and Pycaw. This project detects the distance between your thumb and index finger and maps it to the system's volume level.

## Features

* Real-time hand tracking using MediaPipe
* Adjust volume by changing the distance between thumb and index finger
* Visual volume bar overlay
* Displays current volume percentage and FPS

## Requirements 📦

* Python 3.7+
* OpenCV
* MediaPipe
* Numpy
* Pycaw
* comtypes

You can install all dependencies using pip:

```bash
pip install -r requirements.txt
```

### `requirements.txt` (example)

```txt
opencv-python
mediapipe
numpy
pycaw
comtypes
```

## Installation 🔧

1. **Clone the repository:**

```bash
git clone https://github.com/h3YaSh07Gv1/Gesture-Volume-Control.git
cd GestureVolumeControl
```

2. **Install the dependencies:**

```bash
pip install -r requirements.txt
```

## How to Run ▶️

Make sure you have a working webcam.

Run the main script:

```bash
python GestureVolumeControl.py
```

Move your thumb and index finger closer or farther apart to decrease/increase the volume.

## File Structure 📁

```
GestureVolumeControl/
├── GestureVolumeControl.py       # Main application script
├── HandTrackingMod.py            # Custom hand detection module
├── requirements.txt
├── README.md
└── results/                      # Recordings folder
    ├── HandTrackingRecording.mp4
    └── GestureVolumeControl.mp4
```

## Acknowledgements 🙏

* [MediaPipe](https://google.github.io/mediapipe/) by Google
* [OpenCV](https://opencv.org/)
* [pycaw](https://github.com/AndreMiras/pycaw)