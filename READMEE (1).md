# Car-Detection-Basic-Open-CV



Description: I used __OpenCV Library__ which is is an open source computer vision and machine learning software library.
HaarCascade: It is a machine learning object detection algorithm used to identify objects in an image or video.
With the combination of Python and CV2, image of cars are extracted from video and displayed on windows Screen.

## Haarcascades -

Haar Cascade classifiers are an effective way for object detection. This method was proposed by Paul Viola and Michael Jones in their paper Rapid Object Detection using a Boosted Cascade of Simple Features .Haar Cascade is a machine learning-based approach where a lot of positive and negative images are used to train the classifier.

* Positive images – These images contain the images which we want our classifier to identify.
* Negative Images – Images of everything else, which do not contain the object we want to detect.

## Installation:
1. Below packages to be installed using the CLI :

    - Numpy `pip install numpy`.
    - Matplotlib `pip install matplotlib` (Matplotlib is optional, but recommended since we use it a lot in our tutorials).
    - OpenCV `pip install opencv-python`
    
2. Install all packages into their default locations. Python will be installed to C:/Python27/ in case of Python 2.7.
3. After installation, open Python IDLE. Enter `import numpy` and make sure numpy is working fine.
4. After installation, open Python IDLE and type in the following lines and execute the file (This is just to check if everything is working fine):<br>
  `import numpy`<br>
  `import matplotlib`<br>
  `import cv2 as cv`<br>
  `print( cv.__version__ )`
5. If the file executes without an error, Congratulations, you have successfully completed the installation part.

### You will cover the following topics while building this project:
1) Frame Differencing
2) Image Thresholding
3) Contours
4) Image Dilation

