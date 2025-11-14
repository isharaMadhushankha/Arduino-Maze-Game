<h1>🌀 Arduino Maze Game</h1>

An interactive hardware project that uses two servo motors and a joystick to control a tilting maze platform and guide a ball through obstacles.

📌 Project Overview

The Arduino Maze Game is a hands-on embedded systems project where the player uses a joystick to tilt a maze board. The servo motors rotate the board along the X and Y axes, allowing the ball to move through the maze using gravity.

This project was developed as a group assignment to improve skills in microcontroller programming, servo control, sensor integration, and team-based engineering.

🎮 Features

Two-axis maze movement

Real-time joystick control

Smooth servo motion

Fully mechanical maze setup

Simple and fun gameplay

Beginner-friendly electronics design

🛠️ Hardware Components

Arduino Uno / Mega

2 × SG90 / MG995 Servo Motors

1 × Analog Joystick Module

Maze Platform (custom-built)

Jumper Wires

Servo Mounts

Power Supply / USB Cable

🔌 Circuit Diagram (Description)

Joystick X-axis → Arduino A0

Joystick Y-axis → Arduino A1

Servo 1 (X-axis tilt) → Digital Pin 9

Servo 2 (Y-axis tilt) → Digital Pin 10

Joystick VCC → 5V

Joystick GND → GND

Servo Power → 5V (External recommended)

💻 Code Summary

Reads analog values from the joystick.

Maps joystick movement to servo angle values (0°–180°).

Updates servo positions in real time for smooth gameplay.

Adjustable sensitivity for difficulty control.

👥 Team Members

Ishara Madushanka

Nadeeshana Lahiru Kavinda

Pasan Kalhara

Gunath Tashen

Dulara Jaysanka

🧩 How to Play

Power the Arduino and place the ball at the start position.

Move the joystick to tilt the maze.

Guide the ball through the path without falling into holes.

Reach the finish point to win.

🚀 Future Improvements

Add an OLED display for scoring/timer

Implement sound effects or buzzer feedback

Add automatic reset mechanism

Build a 3D-printed maze frame for durability

Integrate mobile app control via Bluetooth

📘 License

This project is open-source and free to use for learning and experimentation.
