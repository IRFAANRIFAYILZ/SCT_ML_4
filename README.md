# SCT_ML_4

# Hand Gesture Recognition Tool

A Python-based hand gesture recognition application built with MediaPipe, OpenCV, and Tkinter, capable of detecting multiple hand gestures in images, videos, and real-time webcam streams — including the "I Love You" heart hands gesture.

---

# Features

1)Image Gesture Recognition – Upload images to detect gestures.
2) Video Gesture Recognition – Process video files for gesture detection.
3) Real-Time Detection – Recognize gestures live from your webcam.
4) Supported Gestures:

✊ Fist

☝️ One Finger

✌️ Two Fingers (Peace)

🤟 Three Fingers

🖐️ Open Palm

👍 Thumbs Up

👎 Thumbs Down

🫶 "I Love You" with Heart Hands

---

# Requirements

Before running, make sure you have Python 3.10+ installed, along with these packages:

pip install opencv-python mediapipe pillow

---

# How to Run

Clone the repository or save the code as gesture_app.py.

---

# Install dependencies:

pip install opencv-python mediapipe pillow

Run the application:

python gesture_app.py

---

# Usage

Upload Image → Select an image file to detect gestures in.

Upload Video → Select a video file for gesture recognition.

Start Webcam → Activate real-time gesture detection from your camera.

Stop Webcam → Stop the live feed.

---

# Note:

Press Q to quit video playback.

---

# How Gesture Detection Works

1) Uses MediaPipe Hands to detect 21 hand landmarks.
2) Gesture classification is based on relative landmark positions (finger bending, thumb orientation).
3) Special "heart hands" detection uses distance thresholds between both hands’ thumbs and index fingers.

---

# Future Improvements

1) Add more complex gestures (rock sign, OK sign, etc.).
2) Enhance heart hands detection accuracy.
3) Multi-person gesture tracking.

---

# Demo

Gesture	Emoji
Fist	✊
Thumbs Up	👍
Thumbs Down	👎
Peace	✌️
I Love You	🫶
