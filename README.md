# Face-Recognition

This is a demo of running face recognition on live video from your webcam. It's a little more complicated than the other example, but it includes some basic performance tweaks to make things run a lot faster:
1. Process each video frame at 1/4 resolution (though still display it at full resolution)
2. Only detect faces in every other frame of video.

PLEASE NOTE: This example requires OpenCV (the `cv2` library) to be installed only to read from your webcam.
OpenCV is *not* required to use the face_recognition library. It's only required if you want to run this specific demo. If you have trouble installing it, try any of the other demos that don't require it instead.

## requirements

python 3.10
visual studio C++ 2019

pip install cmake
pip install wheel
pip install dlib
pip install face_recognition
pip install open_cv

