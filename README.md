# Hand-Gesture-Presentation-System
Control presentation slides with real-time hand gestures using OpenCV &amp; Mediapipe

# Introduction
This project is an application based on Landmark Detection that allows you to control presentations using hand gestures — no mouse or touchpad needed! It uses Hand Tracking to detect your hand in real-time through your webcam. Whenever the user makes a gesture, it is detected and the associated action is performed automatically.

# Use Case
This is a practical example of using Hand Landmark Detection for real-world tasks — specifically, controlling slides in a presentation with gestures only.

# Functionalities
Currently, this system supports six main actions:
1. Next Slide — go forward
2. Previous Slide — go back
3. Pointer — use your index finger as a virtual pointer
4. Draw — draw annotations on the slide
5. Erase — erase parts of the drawing
6. Clear Screen — clear all drawings

# Main Libraries Used
1. OpenCV — for image capture, processing, and drawing on frames.
2. Mediapipe — for real-time hand tracking and landmark detection.
3. NumPy — for efficient array operations and mask processing.
4. PyAutoGUI — for automating keyboard controls (slide navigation)
