# HandDrawCanvas

A virtual drawing application that allows you to draw, erase, and interact using hand gestures via a webcam. This project uses OpenCV and MediaPipe for hand tracking and gesture recognition, enabling a seamless and interactive drawing experience.

## Features
- **Gesture Recognition**: Use hand gestures to switch between tools, colors, and modes.
- **Selection Mode**: Choose colors and tools by pointing at the virtual header.
- **Drawing Mode**: Draw and erase on a virtual canvas using hand gestures.
- **Real-Time Interaction**: Visualize your drawing and hand movements live on the screen.

## Tech Stack
- **Python**: Programming language.
- **OpenCV**: Computer vision library for image processing.
- **MediaPipe**: Framework for hand tracking and gesture detection.

## How It Works
1. **Hand Detection**: Uses MediaPipe to detect and track hand landmarks.
2. **Gesture Recognition**: Recognizes specific gestures, like raising fingers, to switch between modes and tools.
3. **Drawing on Canvas**: Tracks fingertip positions to draw lines or erase on a virtual canvas.
4. **Dynamic Header**: Updates the header UI to reflect the currently selected tool or color.

## Requirements
- Python 3.7+
- OpenCV 4.5+
- MediaPipe
- Webcam-enabled system

Install the required dependencies using:
```bash
pip install opencv-python mediapipe numpy
