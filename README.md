# AI_Face_Detector
This project focuses on building an AI-based system that detects human faces in pre-recorded videos. The system processes each video frame, identifies facial regions, and highlights them using bounding boxes.
AI FACE DETECTOR 
## Description:
This project focuses on building an AI-based system that detects human faces in real-time or pre-recorded videos. The system processes each video frame, identifies facial regions, and highlights them using bounding boxes. It leverages computer vision techniques and deep learning-based object detection models to accurately locate faces under different lighting conditions, angles, and movements. The detected faces are continuously tracked across frames to ensure consistent identification throughout the video. This project can be applied in surveillance systems, attendance systems, security monitoring, and video analytics. It demonstrates practical implementation of object detection, video processing, and AI model integration using tools like OpenCV and pre-trained face detection models.
## Objective
The main objective of this project is to build an efficient and accurate face detection system capable of detecting multiple faces in different conditions such as:
Varying lighting environments
Different face angles
Real-time video streams or recorded videos
## Libraries Used in AI Face Detection Project (MTCNN + OpenCV)
### 1. OpenCV (cv2)
Used for video processing and image handling.
Key roles:
Reading video files (cv2.VideoCapture)
Extracting frames from video
Drawing bounding boxes around detected faces
Displaying output video in real-time (cv2.imshow)
Saving processed video (cv2.VideoWriter)
### 2. MTCNN (Multi-task Cascaded Convolutional Neural Network)
A deep learning model used specifically for face detection.
Detects:
Face location (bounding boxes)
Facial landmarks (eyes, nose, mouth)
Works very well for:
Angled faces
Low-light conditions
Multiple faces in one frame
Python package: mtcnn
## Features
Detects faces in real-time video or recorded video files
Handles multiple face detection in a single frame
Draws bounding boxes around detected faces
Works under different lighting and face orientations
Easy to extend for face recognition or tracking

