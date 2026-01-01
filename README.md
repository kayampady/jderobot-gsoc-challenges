# Brownian Motion Robot Simulation

This project implements a simple Brownian Motion–based robot behavior as part of the
**JdeRobot GSoC 2025 Python Challenge**.

## Description
The robot is modeled as a point moving inside a square arena.
- The robot starts at the center
- It moves forward continuously
- When it collides with a boundary, it rotates by a random angle
- The motion resembles Brownian/random walk behavior

## Technologies Used
- Python 3
- NumPy
- Matplotlib (for visualization and GIF generation)

## Files
- `brownian-robo.py` – Core Brownian Motion robot simulation
- `brownian-robo-gif.py` – Generates an animated GIF of the robot motion
- `brownian_motion.gif` – Output visualization

## How to Run
```bash
python brownian-robo.py
python brownian-robo-gif.py
