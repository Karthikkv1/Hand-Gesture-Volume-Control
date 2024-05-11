
# Handgesture Volume Control using Python with OpenCV, MediaPipe, and PyAutoGUI

This Python project allows users to control the system's volume using hand gestures captured through a webcam. It utilizes OpenCV for video capture, MediaPipe for hand tracking, and PyAutoGUI for controlling the system's volume.

## Features

- **Hand Gesture Detection**: Detects hand gestures in real-time using a webcam.
- **Volume Control**: Maps hand movements to control system volume, increasing or decreasing based on hand gestures.
- **Interactive Visual Feedback**: Draws landmarks on detected hands and lines between specific landmarks for visual feedback.
- **Adjustable Sensitivity**: Adjusts volume control sensitivity based on the distance between two specified hand landmarks.

## Installation

1. Ensure you have Python installed on your system.
2. Install the required dependencies:
   ```
   pip install opencv-python mediapipe pyautogui
   ```
3. Clone the repository to your local machine:
   ```
   git clone <repository_url>
   ```

## Usage

1. Run the main program using Python:
   ```
   python handgesture_volume_control.py
   ```
2. Position your hand in front of the webcam to start controlling the system volume.
3. Move your thumb and forefinger apart to increase the volume.
4. Bring your thumb and forefinger closer together to decrease the volume.
5. Press the 'Esc' key to exit the application.



## Contributing

Contributions are welcome! If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.



