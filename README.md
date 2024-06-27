# Human Detection Using YOLO Model on Linux

This project demonstrates how to set up and run human detection using the YOLO (You Only Look Once) model on a Linux system. The YOLO model is used to detect humans in real-time via a webcam.

## Prerequisites

- Python 3.x
- pip

## Installation


Install Dependencies
1. ```sh sudo apt-get update
sudo apt-get upgrade
sudo apt-get install python3-pip python3-venv

pip3 install numpy opencv-python

Step 2: Set Up Virtual Environment (Recommended)
sh
python3 -m venv yolov3-env
source yolov3-env/bin/activate

Step 3: Install Python Packages
sh
pip install numpy opencv-python

Step 4: Download YOLOv3 Files
sh
wget https://pjreddie.com/media/files/yolov3.weights
wget https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolov3.cfg
wget https://raw.githubusercontent.com/pjreddie/darknet/master/data/coco.names

Step 5: Create Python Script
Create a file named human_detection.py with the content given in repository

Troubleshooting
Webcam Connection: Ensure your webcam is properly connected and recognized by the system.
File Paths: Verify that the paths to the YOLO weights, config, and COCO names files are correct in the script.
Dependencies: Ensure all required dependencies are installed in your virtual environment.

By following these steps, you should be able to set up and run human detection using the YOLO model on a Linux system successfully. If you encounter any issues, please report
