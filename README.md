# Parking Space Detection System

This repository contains a Python script for detecting free and occupied parking spaces inside a parking lot. The script uses OpenCV to capture a video stream from a camera and then applies image processing techniques to detect parked cars and determine whether the parking space is occupied or not.

## Files Included

This repository includes the following files:

- `code projet raspbeerry.py`: the main Python script that implements the parking space detection system.
- `label.txt`: a file containing the labels used in the object detection model.

## System Requirements

The parking entry system requires the following:

- Raspberry Pi or any other computer with a camera
- OpenCV-Python
- TensorFlow Lite
- Firebase Firestore

## Usage

To use this script, follow these steps:

1-Install the required dependencies:

```
pip3 install opencv-python
sudo apt-get install libcblas-dev
sudo apt-get install libhdf5-dev
sudo apt-get install libhdf5-serial-dev
sudo apt-get install libatlas-base-dev
sudo apt-get install libjasper-dev
sudo apt-get install libqtgui4
sudo apt-get install libqt4-test
echo "deb https://packages.cloud.google.com/apt coral-edgetpu-stable main" | sudo tee /etc/apt/sources.list.d/coral-edgetpu.list
curl https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key add -
sudo apt-get update
sudo apt-get install python3-tflite-runtime
```

2-Clone this repository to your local machine.

3-Install the required Python libraries.

4-Configure the `code projet raspbeerry.py` script with your Firebase Firestore database credentials.

5-Connect your camera to the system and run the `code projet raspbeerry.py` script.
