# Drowsiness Detection System using MediaPipe

A real-time **driver drowsiness detection system** built with Python, OpenCV, and MediaPipe.  
The system monitors eye movement using facial landmarks and triggers an alarm when drowsiness is detected.

## Features
- Real-time face and eye tracking
- Eye Aspect Ratio (EAR) based drowsiness detection
- Alarm alert when eyes remain closed for a set duration
- Mirror view toggle
- Lightweight and works with a normal webcam

## Tech Stack
- Python
- OpenCV
- MediaPipe
- NumPy
- SciPy
- Threading
- Winsound (Windows)

## How It Works
1. Webcam captures video frames.
2. MediaPipe detects facial landmarks.
3. Eye landmarks are extracted.
4. Eye Aspect Ratio (EAR) is computed.
5. If EAR stays below a threshold for several frames, drowsiness is detected.
6. Alarm sound alerts the user.

## Requirements
Install dependencies using:

```bash
pip install opencv-python mediapipe numpy scipy
