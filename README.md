###Installation
Requires python and pip installer, 

Use the terminal and this command to install:
pip install mediapipe opencv-python

#Description
A python application using mediapipe and opencv to track the number of bicep curls that
a user has completed. Uses mediapipe's pose detection library to track joints.
The elbow joint angle is calculated using trigonometry and the relative angle between the left shoulder, left elbow
and left wrist. From this, the stage of the bicep curl is found. If the angle is greater than 160 degrees,
it is in the down position, however when it reaches < 30 degrees, it is in the up position.
When the arm transitions between these two stages, the counter is incremented.

I had a lot of fun making this project, and I hope you enjoy using it!

#Usage:
python BicepCurlCounter.py

