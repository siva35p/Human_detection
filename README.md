This is a project on how to setup and run human detection using the YOLO(You Only Look Once) model on linux. The model deployed over here is a YOLO model to detect humans in real-time from the web-cam. 

Prerequisites 
Python 3.x 
pip 

Installation 
steps 

Step 1: Install Dependencies 
sudo apt-get update 
sudo apt-get upgrade 
sudo yum install python3-pip python3-venv 

On non-archlinux based systems, you can install the required dependencies using: 

In the second Step: Set Environment // Highly recommended to set Virtual environment 
sh 
python3 -m venv yolov3-env 
yolov3-env/bin/activate 

Before running the code import following python packages like 
sh 
pip install numpy opencv-python 

Step 4: Download YOLOv3 Files 
sh 
wget https://pjreddie.com/media/files/yolov3.weights 
wget https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolov3.cfg 
wget https://raw.githubusercontent.com/pjreddie/darknet/master/data/coco.names 

Usage 
Step 5: Create Python Script 
