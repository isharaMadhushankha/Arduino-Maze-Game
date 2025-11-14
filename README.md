<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">

</head>
<body>

<h1>🌀 Arduino Maze Game</h1>
<p>An interactive hardware project that uses <b>two servo motors</b> and a <b>joystick</b> to control a tilting maze platform and guide a ball through obstacles.</p>

<h2>📌 Project Overview</h2>
<p>The <b>Arduino Maze Game</b> is a hands-on embedded systems project where the player uses a joystick to tilt a maze board. The servo motors rotate the board along the <b>X and Y axes</b>, allowing the ball to move through the maze using gravity.</p>
<p>This project was completed as a group assignment to strengthen skills in <b>microcontroller programming</b>, <b>servo control</b>, <b>sensor integration</b>, and <b>team-based engineering</b>.</p>

<h2>🎮 Features</h2>
<ul>
    <li>Two-axis maze movement</li>
    <li>Real-time joystick control</li>
    <li>Smooth servo motion</li>
    <li>Fully mechanical maze setup</li>
    <li>Simple and fun gameplay</li>
    <li>Beginner-friendly electronics design</li>
</ul>

<h2>🛠️ Hardware Components</h2>
<ul>
    <li>Arduino Uno / Mega</li>
    <li>2 × SG90 / MG995 Servo Motors</li>
    <li>1 × Analog Joystick Module</li>
    <li>Maze Platform (custom-built)</li>
    <li>Jumper Wires</li>
    <li>Servo Mounts</li>
    <li>Power Supply / USB Cable</li>
</ul>

<h2>🔌 Circuit Diagram (Description)</h2>
<ul>
    <li>Joystick X-axis → Arduino A0</li>
    <li>Joystick Y-axis → Arduino A1</li>
    <li>Servo 1 (X-axis tilt) → Digital Pin 9</li>
    <li>Servo 2 (Y-axis tilt) → Digital Pin 10</li>
    <li>Joystick VCC → 5V</li>
    <li>Joystick GND → GND</li>
    <li>Servo Power → 5V (External recommended)</li>
</ul>

<h2>💻 Code Summary</h2>
<ul>
    <li>Reads analog values from the joystick.</li>
    <li>Maps joystick movement to servo angles (0°–180°).</li>
    <li>Updates servo positions in real time for smooth gameplay.</li>
    <li>Adjustable sensitivity for difficulty control.</li>
</ul>

<h2>👥 Team Members</h2>
<ul>
    <li>Ishara Madushanka</li>
    <li>Nadeeshana Lahiru Kavinda</li>
    <li>Pasan Kalhara</li>
    <li>Gunath Tashen</li>
    <li>Dulara Jaysanka</li>
</ul>

<h2>🧩 How to Play</h2>
<ol>
    <li>Power the Arduino and place the ball at the start position.</li>
    <li>Move the joystick to tilt the maze.</li>
    <li>Guide the ball through the path without falling into holes.</li>
    <li>Reach the finish point to win.</li>
</ol>

<h2>🚀 Future Improvements</h2>
<ul>
    <li>Add an OLED display for scoring/timer</li>
    <li>Implement sound effects or buzzer feedback</li>
    <li>Add automatic reset mechanism</li>
    <li>Build a 3D-printed maze frame</li>
    <li>Integrate mobile app control via Bluetooth</li>
</ul>

<h2>📘 License</h2>
<p>This project is open-source and free to use for learning and experimentation.</p>

</body>
</html>
