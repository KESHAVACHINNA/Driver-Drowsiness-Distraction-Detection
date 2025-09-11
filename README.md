# Driver-Drowsiness-Distraction-Detection

Project Overview

The Driver Drowsiness & Distraction Detection System is a real-time computer vision application designed to enhance road safety. It monitors a driver’s face to detect drowsiness (sleepiness) and distractions (looking away from the road) and triggers timely alerts to prevent accidents.

This system is ideal for automotive safety research, fleet management, and smart vehicle applications.

Key Features

# Real-Time Monitoring: Detects driver alertness via webcam feed.

# Drowsiness Detection: Monitors eye closure (EAR) and yawning (MAR).

# Distraction Detection: Detects inattentiveness using head/gaze tracking.

# Custom Alerts: Audible and visual warnings when thresholds are crossed.

# Configurable Thresholds: Adjust sensitivity based on individual drivers.

System Architecture
[Webcam Input] --> [Face Detection] --> [Landmark Detection] --> [EAR/MAR Calculation] --> [Drowsiness/Distraction Alerts]


Flow Diagram Placeholder
(Insert Figure: System Workflow here)

Installation

Clone the repository:

git clone https://github.com/USERNAME/Driver-Drowsiness-Distraction-Detection.git
cd Driver-Drowsiness-Distraction-Detection


Create a virtual environment:

python -m venv venv
# Windows
venv\Scripts\activate
# macOS/Linux
source venv/bin/activate


Install dependencies:

pip install -r requirements.txt

Usage

Ensure your webcam is connected.

Run the main script:

python driver_monitor.py


The system will:

Detect your face and eyes in real-time.

Monitor drowsiness and distraction.

Trigger alerts if thresholds are exceeded.
