# OpenCV_Python_Tutorials
Scripts which will help beginners to get a good understanding of how things work in OpenCV using Python

Few points/fixes for OpenCV:
1) For parameters where you have to type in a text like cv2.CAP_PROP_FPS and you get a error.
   If you are in OpenCV version 2.4 then type cv2.cv.CV_CAP_PROP_FPS. In OpenCV Ver 3 this error doesnt occour.
   ".cv.CV_" -> This is the phrase added.
