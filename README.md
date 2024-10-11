# Gesture Controller

This project enables controlling system functions such as brightness, volume, scrolling, and mouse interactions using hand gestures. It utilizes **OpenCV**, **Mediapipe**, and **PyAutoGUI** to detect and map hand gestures to various system controls, making interaction touch-free.

## Features

- **Mouse Control**: Move the mouse cursor, left-click, right-click, and double-click using hand gestures.
- **System Brightness Control**: Adjust the screen brightness by pinching gestures.
- **System Volume Control**: Change system volume with hand gestures.
- **Scrolling**: Scroll vertically and horizontally using hand gestures.
- **Gesture Recognition**: Detects a variety of hand gestures like fist, palm, pinch, V-sign, and others.

## Dependencies

- **OpenCV**: For capturing video frames from the webcam.
- **Mediapipe**: For hand landmark detection.
- **PyAutoGUI**: For controlling mouse and keyboard interactions.
- **Screen Brightness Control**: For adjusting system brightness.
- **PyCaw**: For controlling system volume.

### Install dependencies:

```bash
pip install opencv-python mediapipe pyautogui screen-brightness-control pycaw
