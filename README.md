<h1 align="center">✋ Hand Gesture Recognition using OpenCV and Python</h1>

<p align="center">
This project implements a <strong>real-time hand gesture recognition system</strong> using computer vision techniques.<br>
It detects the number of fingers shown to a webcam and dynamically displays the count on the screen.
</p>

---

<h2 align="center">🔍 Features</h2>

- 🎥 Real-time finger count detection using a webcam  
- ✋ ROI-based hand tracking  
- 🧼 Background subtraction with accumulated weighted averaging  
- 🌀 Contour and convex hull-based gesture segmentation  
- 🔵 Circular ROI for detecting finger tips  
- 🖼️ Live feedback with OpenCV overlays  

---

<h2 align="center">🧠 Tech Stack</h2>

- 🐍 Python  
- 📷 OpenCV  
- 🔢 NumPy  
- 🧮 scikit-learn *(for pairwise distance calculation)*  

---

<h2 align="center">🚀 How It Works</h2>

1. Captures video from the webcam.  
2. Establishes background over the first 60 frames.  
3. Detects hand region using background subtraction.  
4. Segments the hand and identifies finger tips using contour analysis.  
5. Displays the detected finger count in real time.

---

<h2 align="center">🎯 Use Cases</h2>

- Touchless gesture-based interfaces  
- Sign language recognition  
- Smart home or IoT control systems  
- AR/VR hand interaction modules  

---

<h2 align="center">▶️ Run It</h2>

```bash
pip install opencv-python numpy scikit-learn
python hand_gesture_recognition.py
