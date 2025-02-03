# Air-Canvas
Hand Gesture Controlled Paint Application

This Python script implements a **hand gesture-controlled painting application** using **OpenCV** and **MediaPipe**. The application allows users to draw on a virtual canvas using their fingertips detected through the webcam feed. 

### Key Features
- **Real-Time Hand Detection**: Utilizes MediaPipe's `Hands` solution to detect hand landmarks.
- **Gesture Control**: Users can select colors or clear the canvas using predefined gesture zones.
- **Color Palette**: Supports four colors - Blue, Green, Red, and Yellow.
- **Canvas Reset**: A "CLEAR" button to reset the drawing canvas.
- **Smooth Drawing**: Points are stored in deque objects for smooth line drawing.

### Usage
1. Run the script.
2. Use your index finger to draw within the webcam feed.
3. Select colors or clear the canvas by pointing at the buttons.
4. Press `q` to exit the application.

### Requirements
- Python 3.x
- OpenCV
- NumPy
- MediaPipe

This program demonstrates the integration of AI-powered hand tracking with interactive graphical applications.
