# Vehicle_Speed-Number_Plate_Detection
Final Project CS 584 Machine Learning

#Guide to run & setup this project

To run vehicle_speed.py, follow these steps below:

Download IDLE python from this site: 'https://www.python.org/downloads/'

Install OpenCV and dlib libraries from: 'https://www.learnopencv.com/install-dlib-on-windows/'

Install these other libraries as well: skimage, sklearn, openpyxl, threading, time, joblib, numpy, matplotlib, datetime, & os.

Through Command Prompt, run this code. (Make sure to change the directories)

Technologies used :

Python
opencv
dlib

Tasks breakdown

Vehicle Detection
We are using Haarcascade classifier to identify vehicles.
Vehicle Tracking - ( assigning IDs to vehicles )
We have used corelation tracker from dlib library.
Speed Calculation
We are calculating the distance moved by the tracked vehicle in a second, in terms of pixels, so we need pixel per meter to calculate the distance travelled in meters.
With distance travelled per second in meters, we will get the speed of the vehicle.
How to run project?
Follow steps:

Clone repo : git clone https://github.com/kraten/vehicle-speed-check

cd (change directory) into vehicle-speed-check cd vehicle-speed-check

Create virtual environment python -m venv venv

Activate virtual environment ./venv/bin/activate

Install requirements pip install -r requirements.txt

run speed_check.py script python speed_check.py
