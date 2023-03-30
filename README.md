# Drowsiness-Detection-System

Drowsiness Detection using Facial Landmarks
This project aims to detect drowsiness in real-time using facial landmarks. The system uses a camera to capture the face of the user and detects facial landmarks using the dlib library. The detected landmarks are then used to calculate the eye aspect ratio (EAR) and mouth aspect ratio (MAR) to determine if the user is drowsy.

Prerequisites

Python 3

OpenCV

dlib

imutils


Algorithm

The system uses a combination of eye aspect ratio (EAR) and mouth aspect ratio (MAR) to detect drowsiness. EAR is calculated as the ratio of distances between the horizontal landmarks and the vertical landmarks of the eye. MAR is calculated as the ratio of distances between the upper lip and the lower lip and the width of the mouth. If the EAR and MAR values are below a certain threshold for a certain amount of time, the system will alert the user.

Credits

The algorithm used in this project is based on the work of Soukupová and Čech in their paper "Real-time Eye Blink Detection using Facial Landmarks".
