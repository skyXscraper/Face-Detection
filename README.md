# Face-Detection

This repository contains a face detection model that identifies and locates a human face in a live feed.
The model is capable of:

1.Detecting multiple faces through a webcam
2.Providing bounding boxes around the detected faces
3.Handling varying lighting conditions and facial orientations
4.Runs efficiently on a standard laptop webcam

Prerequisites

1.Python 3.7+
2.OpenCV

How to use:

1.Clone the Repository
Start by cloning the repository and navigating into the project directory

2.Import the FrontalFace xml file from haarcascade

3.Run the Model
You can run the face detection model on your webcam,the webcam feed is captured using OpenCV. The face detection model processes each frame and returns bounding box coordinates for each detected face.

4.Real-Time Performance
The model is optimized for real-time performance and should run efficiently on most machines.
