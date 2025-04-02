 Hand Gesture Volume Control
overview
Hand Gesture Volume Control is a Python-based project that allows users to adjust system volume using hand gestures. Utilizing computer vision and machine learning techniques, the system tracks hand movements in real time to control volume without physical input devices.

Features
- Real-time Hand Tracking – Uses a webcam to detect and track hand gestures.
- Gesture-Based Volume Control – Adjusts system volume dynamically based on finger positioning.
- Lightweight & Efficient – Works on low-end PCs with minimal processing power.
- Touch-Free Interaction – Provides a seamless, hands-free experience.

How It Works
- The webcam captures the user's hand movements.
- Mediapipe detects hand landmarks and tracks finger positions.
- Based on the distance between the thumb and index finger, Pycaw adjusts the system volume.
- OpenCV displays a real-time visual interface for user feedback.

To run 
python run.py

