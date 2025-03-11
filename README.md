#Weapon Detection using OpenCV

##📌 Overview

This project implements a Weapon Detection System using OpenCV and Python. The program captures real-time video from a webcam and uses a Haar cascade classifier to detect objects. Currently, it is set to detect faces (as a placeholder for weapon detection).

##🚀 Features

Real-time object detection using OpenCV

Webcam-based live feed processing

Highlights detected objects with a bounding box

Displays detection status in the terminal

##🛠️ Requirements

Ensure you have the following installed:

Python 3.x

OpenCV (opencv-python)

Imutils (imutils)

NumPy (numpy)

##📥 Installation

Clone the repository and install the required dependencies:

# Clone this repository
git clone https://github.com/divyabansal24/WeaponDetection.git
cd WeaponDetection

# Install dependencies
pip install opencv-python imutils numpy

▶️ Usage

Run the script to start the weapon detection system:

python weapon_detection.py

Press 'q' to exit the program.

##📝 Code Explanation

Captures video from the webcam using OpenCV.

Converts frames to grayscale for better processing.

Uses a Haar cascade classifier (haarcascade_frontalface_default.xml) to detect objects.

Draws a bounding box around detected objects.

Displays real-time feed with detected objects highlighted.

##🔧 Future Improvements

Train a custom cascade classifier for actual weapon detection.

Implement deep learning-based detection (e.g., YOLO, SSD, or Faster R-CNN).

Add alert mechanisms when a weapon is detected.

##🤝 Contributing

Feel free to fork this repository and submit pull requests for improvements!
