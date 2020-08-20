# Face-recognition-in-Friends-TV-show-using-Deep-Learning

Tool used:

1. Dlib - Dlib is an open-source library built using C++. It contains various machine learning and deep learning models which can be used to solve real-world problems. It contains various models for performing face detection, face recognition and face pose estimation. Davis King, the creator of dlib has created a model that can be used creating 68 key facial landmarks that map the structure of a human face. This pre-trained model estimates the location of 68 (X, Y) coordinates.

2. OpenCV - OpenCV is an open source library built for performing digital visualisation analyses. It can be used to perform image and video editing, image and video processing, face detection and recognition etc. It can also be used to make Machine Learning and Deep Learning models with OpenCV AI kit.

3. Face_recognition API - Face_recognition API is created by Adam Geitgey. It uses the dlib facial recognition network to generate 128-d feature vector of the detected face and uses a triplet training step for training the network and comparing the results for face recognition.

## Usage:
python recognize_faces_video_file.py --encodings encodings.pickle --input videos/example.mp4 --output output/example_output.avi --display 0

## Files: 

+ search_bing_api.py : Build a dataset using the Bing API.

+ encode_faces.py : Encodings (128-d vectors) for faces are built with this script.

+ recognize_faces_image.py : Recognize faces in a single image (based on encodings from your dataset).

+ recognize_faces_video.py : Recognize faces in a live video stream from your webcam and output a video.

+ recognize_faces_video_file.py : Recognize faces in a video file residing on disk and output the processed video to disk. I won’t be discussing this file today as the bones are from the same skeleton as the video stream file.

+ encodings.pickle : Facial recognitions encodings are generated from your dataset via encode_faces.py and then serialized to disk.

## Acknowledgement: 

https://www.pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/
