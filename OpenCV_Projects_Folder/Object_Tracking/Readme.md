# Real Time Object Tracking with Optical Flow with OpenCV

## Overview

In this project Real-Time Feature Tracking System is being used with Optical Flow through Webcam with algorithms
- **Shi-Tomasi Corner Detection**
- **Lucas-Kanade Optical Flow (Pyramidal)**

The system detects strong feature points in a video stream and tracks their motion across consecutive frames, visualizing trajectories and movement patterns in real time.

## System Architecture Layered

1. Webcam Input
2. Frame Preprocessing (Grayscale Conversion)
3. Feature Detection (Initial Frame)
4. Optical Flow Tracking (Frame-to-Frame)
5. Filtering Valid Points
6. Visualization (Tracks + Points)

<img width="657" height="539" alt="Screenshot from 2026-04-16 03-15-33" src="https://github.com/user-attachments/assets/09164082-2cc7-4b3b-99c1-f88c9547e677" />
<img width="657" height="539" alt="Screenshot from 2026-04-16 03-19-21" src="https://github.com/user-attachments/assets/66ca6f19-179a-4fb8-8ff9-a10868640e2e" />

## Requirements
- Python3
- OpenCV
- Numpy

## Install Dependencies
```
pip install opencv-python numpy
```
## Run

```
python3 optical_flow_tracking.py
```

## Controls
1. ESC -> Exit the Program
2. R -> Reset Tracking
3. C -> Clear Trajectory Lines
