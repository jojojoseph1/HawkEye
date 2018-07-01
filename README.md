# HawkEye
This is a concept on intrusion detection using Python libraries face detection and OpenCV


## This is done on Linux and Windows Platforms(Might work on MacOS) 
* The face recognition model might not work well on children as it is trained for the adults.
`(The features in Adults are easy to identify and almost every small child looks same)`
 

## Install face recognition with pip
```Linux
pip install face_recognition
```

__You need OpenCV too__:
```
pip install OpenCV
```
(**All the requirements are specified in requirements.txt**)



* If you cannot install opencv on windows,then go the link below:
[https://docs.opencv.org/3.0-beta/doc/py_tutorials/py_setup/py_setup_in_windows/py_setup_in_windows.html]



#### Remember that the images used in the above program are our own, in the place of `first_image object` in `Video_Face_Recognition.py` give an image from your local directory
``(You can also make use of a server and get photos from the server and make comparisons with those too)``




### This code uses Twilio API to send messages in case of any intruder detection,(This can be done by a webcam):
![alt text](https://github.com/jojojoseph1/HawkEye/blob/master/Screenshot%20from%202018-07-01%2010-45-43.png "Unknown Image")

### The above person is unknown,this is where Twilio API comes into picture,(with an access token) we can send messages to a specific number about the intruder:
![alt text](https://github.com/jojojoseph1/HawkEye/blob/master/Screenshot_20180701-104844.jpg "Message")


** If the match occurs,The Name given in the arraylist in the program would be shown:
![alt text](https://github.com/jojojoseph1/HawkEye/blob/master/Screenshot%20from%202018-06-30%2013-28-32.png "Face Detection")

