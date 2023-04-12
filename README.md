# Face Recognition using OpenCV
This project demonstrates a simple face recognition system using OpenCV and the Haar Cascade classifiers. The system captures video from the camera, detects faces, and recognizes them using machine learning algorithms.

<img src="https://user-images.githubusercontent.com/61319491/231354128-1f3d492d-e343-4fcd-8562-5af13f3bfe4a.jpeg" alt="work12" width="400" height="400">

## Features
- Face detection using Haar Cascade classifiers
- Face recognition using Local Binary Patterns Histograms (LBPH) Face Recognizer
- Training the recognizer with images
- Real-time face recognition from the video stream
- Saving and loading face data using Pickle

## Prerequisites
- Python 3.6 or later
- OpenCV
- NumPy
- Pillow (PIL)
- Pickle

## Usage
- Clone the repository or download the source code.
- Install the required packages using the following command:

```
  pip install -r requirements.txt
```
Run the Python scripts for training the recognizer and performing real-time face recognition.

## Description
This project contains three Python scripts:

- train.py - This script preprocesses the images, detects faces using Haar Cascade classifiers, trains the LBPH face recognizer, and saves the trained data and labels.

- faces.py- This script captures the video stream from the camera, detects faces, and recognizes them using the trained data. The recognized person's name is displayed on the video stream.

- detect.py - This script captures the video stream from the camera and detects faces using Haar Cascade classifiers. It demonstrates face detection without the recognition functionality.

