This is a simple program that detects faces in images.

It uses Python, OpenCV, numpy and matplotlib.

The OpenCV library contains pretrained models that can be used for face detection.

The model used here is called: Haar cascade classifier for face detection.

The first step is to use the numpy library to convert the input image into a form that is suitable for OpenCV to work with.

We then import the OpenCV library and load the face detection model.

We then use the model to detect faces in the image specified and then
draw bounding circles on the detected faces.

We then show the image containing the detected faces using the matplotlib library.

The matplotlib library is a python library that is used for creating visualisations in python.
