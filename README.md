# FaceDetection
Description:
The provided code demonstrates facial detection using the MTCNN (Multi-task Cascaded Convolutional Networks) model in combination with OpenCV (Open Source Computer Vision Library) for both images and live video streams.

single_image_detection.py:
This script performs facial detection on a single image (vk.jpg). It uses the MTCNN model to detect faces and highlights facial landmarks such as eyes, nose, mouth, etc., by drawing circles around them. Additionally, bounding boxes are drawn around detected faces.

live_video_detection.py:
This script captures live video from the default camera (VideoCapture(0)) using OpenCV. It continuously detects faces in the live video stream using the MTCNN model and draws bounding boxes around the detected faces. The live video feed is displayed in a window, and the program exits when the 'x' key is pressed.

This description provides a brief overview of the functionality of the two scripts for facial detection using MTCNN and OpenCV.
