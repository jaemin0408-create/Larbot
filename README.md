# Project Title
Larbot
## Description
Autonomous rover using Raspberry Pi and sensors for navigation.

## Hardware
- Raspberry Pi
- Camera
- RPLIDAR
- Motor driver

## Software
- Python 3
- OpenCV
- NumPy
- rplidar

## How to Run
## Installation
sudo apt update
sudo apt upgrade -y
sudo apt install python3-pip -y
pip3 install opencv-python numpy rplidar tensorflow==2.15.0

## Clone the Repository
git clone https://github.com/USERNAME/REPOSITORY_NAME.git
cd REPOSITORY_NAME

## Run the Program
python3 main.py

## Notes

Ensure the LiDAR device port is correctly set (e.g., /dev/ttyUSB0).

Place the rover on a stable surface before running the program.

Stop the program safely using Ctrl + C.
