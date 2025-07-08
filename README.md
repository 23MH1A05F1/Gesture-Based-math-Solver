# Gesture-Based-math-Solver
Solving math problem with just your hands - no keybord , no mouse , no calculator .
 What is a Gesture-Based Math Solver?
A Gesture-Based Math Solver is an interactive Python app that:

Tracks your hand movements
Recognizes how many fingers you show
Converts those into numbers or operations
Evaluates the expression in real-time
All using just your webcam + hands + Python magic!

Tech Stack Used :

Tool	- Purpose
Python -	Main programming language
OpenCV	-Capture and display webcam input
MediaPipe -	AI-powered hand tracking (21 keypoints/hand)
NumPy -	Math calculations (like finger distance)
eval() -	Python’s built-in method to evaluate math

📷 How it Works – Behind the Scenes :

Step-by-Step Process:

Start Webcam
OpenCV captures your video feed in real time.
Detect Hands
MediaPipe finds and tracks your hand landmarks (21 points per hand).
Count Fingers
Logic checks which fingers are up or down to detect:
Numbers (0–9)
Operators (+, −, ×, ÷)
Commands (=, delete, clear, exit)
Build Math Expression
Each gesture adds a part to the expression.
Evaluate Expression
Show the “equal” gesture to solve it.
