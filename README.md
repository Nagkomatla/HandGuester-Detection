✋ Hand Gesture Recognition using OpenCV and Python
This project implements a real-time hand gesture recognition system using computer vision techniques. It detects the number of fingers shown to a webcam and displays the count dynamically on the screen.

🔍 Features
🎥 Real-time finger count detection using a webcam

✋ ROI-based hand tracking

🧼 Background subtraction with accumulated weighted averaging

🌀 Contour and convex hull-based gesture segmentation

🔵 Circular ROI for detecting finger tips

🖼️ Live feedback with OpenCV overlays

🧠 Tech Stack
🐍 Python

📷 OpenCV

🔢 NumPy

🧮 scikit-learn (for pairwise distance calculation)

🚀 How It Works
Captures video from the webcam.

Establishes background over the first 60 frames.

Detects hand region using background subtraction.

Segments the hand and identifies finger tips using contour analysis.

Displays the detected finger count in real time.

🎯 Use Cases
Touchless gesture-based interfaces

Sign language recognition

Smart home or IoT control systems

AR/VR hand interaction modules

▶️ Run It
bash
Copy
Edit
pip install opencv-python numpy scikit-learn
python hand_gesture_recognition.py
