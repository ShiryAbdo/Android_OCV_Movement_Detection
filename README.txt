This project contains two tech demos using the OpenCV Android library. A sample app is provided on the app store at https://play.google.com/store/apps/details?id=com.ocv.objectdetect

The CameraOCVDetect folder contains the code that uses the BackgroundSubtractorMOG algorithm from the OpenCV library to detect movement from the smartphone/tablet's camera and draws some contours around the objects that are moving.

The FoscamOCVDetect folder contains the code that uses Foscam data, which is a wireless camera that it broadcasts its feed online, by taking a snapshot of the current frame before using the BackgroundSubtractorMOG algorithm to detect movement and draw contours.

In order to utilize both libraries, the OpenCV Manager must be first installed on the Android device and more information about adding OpenCV to Android apps can be found at: http://opencv.org/