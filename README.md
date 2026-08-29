✋ Mediapipe-HandFX
Real-time hand-tracking visual effects powered by MediaPipe and OpenCV — turn your hand movements into interactive on-screen magic.
�
￼ ￼ ￼ 


�
￼ ￼ ￼ ￼ 


📖 Overview
Mediapipe-HandFX uses Google's MediaPipe Hands solution to detect and track 21 hand landmarks in real time from a webcam feed, then maps those landmarks to interactive visual effects — think gesture-controlled particle trails, virtual drawing, glowing fingertip effects, and more. Built entirely with Python, OpenCV, and MediaPipe — no heavy game engine required.
✨ Features
🖐️ Real-Time Hand Tracking — Detects 21 3D landmarks per hand using MediaPipe
🎆 Dynamic Visual Effects — Fingertip trails, glow effects, particles, or gesture-triggered animations
🎯 Gesture Recognition — Trigger different effects based on hand pose/gesture
🖥️ Live Webcam Feed — Works directly with your default camera, no extra hardware needed
⚡ Lightweight & Fast — Runs smoothly on CPU, no GPU required
🔧 Easy to Extend — Simple, modular code structure for adding your own custom effects
🖥️ Demo
Add a screen recording or GIF here showing the hand-tracking effects in action.
Code
🛠️ Built With
HTML,CSS and J's — Core language
OpenCV — Video capture and rendering
MediaPipe — Hand landmark detection
NumPy — Numerical operations for effect calculations
📂 Project Structure
Plaintext
Mediapipe-HandFX/
├── index.html            # Entry document (video & canvas elements)
├── css/
│   └── style.css         # Styling for canvas overlay, UI controls, and layout
├── js/
│   ├── app.js            # Main entry script (webcam loop & engine runner)
│   ├── handTracking.js   # MediaPipe Hands JS initialization wrapper
│   ├── effects/
│   │   ├── trailEffect.js # Particle and trail rendering on Canvas
│   │   └── glowEffect.js  # Fingertip glow highlight rendering
│   └── utils/
│       └── helpers.js    # Canvas geometry & math utilities
└── README.md             # Project documentation
Code
ℹ️ Update this tree to match your actual file names and module layout.
🚀 Getting Started
Prerequisites
A working webcam
pip
Installation
Clone the repository
Bash
(Recommended) Create a virtual environment
Bash
Install dependencies
Bash
If there's no requirements.txt yet, at minimum you'll need:
Bash
Usage
Run the main script and allow camera access:
Bash
Position your hand in front of the webcam
Move your fingers to trigger the visual effects
Press q to quit the application
🎮 Controls
Key
Action
q
Quit the application
s
Save a screenshot (if implemented)
c
Clear the canvas/trail (if implemented)
ℹ️ Update this table with your actual keybindings.
🎨 Customization
You can tweak effect parameters (color, trail length, particle size, sensitivity) directly in the relevant effect module — for example:
Python
🗺️ Roadmap
[ ] Add more gesture-based effect triggers
[ ] Support multi-hand effects simultaneously
[ ] Export recorded sessions as video
[ ] Add a simple effect-selection UI
🤝 Contributing
Contributions, issues, and feature requests are welcome!
Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
📄 License
This project is licensed under the MIT License — see the LICENSE file for details.
👤 Author
Saadullah
GitHub: @saadullah990123
⭐ Show Your Support
If you found this project interesting, give it a ⭐ on GitHub!
