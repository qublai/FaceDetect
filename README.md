# FaceDetect
Simple Python program for face detection using OpenCV and your PC camera
Usage:
1.	Clone this repository or download the face_detection.py file.
2.	Run the face_detection.py program:
bash
python face_detection.py
3.	The program will open a window showing your camera's feed with detected faces framed in green rectangles.
4.	Press 'q' to exit the program.
Note:
•	Make sure to have a working camera (usually the built-in webcam) and a well-lit environment for better face detection results.
•	You can change the parameters for face detection to fine-tune the detection process, like scaleFactor, minNeighbors, and minSize in the cv2.CascadeClassifier.detectMultiScale function.
•	The program uses the pre-trained Haar Cascade classifier for face detection. You can explore other pre-trained models for more advanced detection tasks.
Author:
QK

