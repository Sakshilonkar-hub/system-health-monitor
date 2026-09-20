# System Health Monitor
A Python script that tracks CPU, memory, and disk usage, logs readings
to a file, and raises an alert when a threshold is exceeded.

## Setup
pip install psutil

## Run
python health_monitor.py

Thresholds can be changed at the top of the script.

## Demo
Lowering the memory threshold to 50% triggers an alert (see alert_demo.png).
