
**Driver Drowsiness Detection System**

This project aims to detect driver drowsiness to prevent road accidents caused by drowsy driving. 
The system uses computer vision techniques to monitor the driver's facial expressions and eye movements to detect signs of drowsiness.


**Introduction**

Driver drowsiness detection is a safety technology that can prevent accidents caused by drivers falling asleep behind the wheel.
This system uses a camera to capture the driver's facial expressions and eye movements and applies machine learning algorithms to detect drowsiness.

**Features**

Real-time drowsiness detection
Alerts the driver when drowsiness is detected
Uses OpenCV for image processing
Utilizes machine learning models for drowsiness detection

**Installation**
**Prerequisites**
Python 3.6 or higher
OpenCV
dlib
imutils
NumPy
SciPy
scikit-learn
Steps
Clone the repository:
1.git clone https://github.com/khushboo9761/driver_drowsiness_detection.git
cd driver_drowsiness_detection

2.Create and activate a virtual environment:
python -m venv venv

source venv/bin/activate   # On Windows use `venv\Scripts\activate`

3.Install the required packages:

pip install -r requirements.txt

4.Download the shape predictor model:

wget http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
bzip2 -d shape_predictor_68_face_landmarks.dat.bz2

1. Ensure your webcam is connected.

2. Run the following command to start the detection system
   python detect_drowsiness.py
   
  ![Train image](../screenshots/Screenshot 2024-05-30 065138.png)
