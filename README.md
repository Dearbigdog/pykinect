# pykinect

Tried again setting the env for kinect2.0 + python2.7

## step1: git clone libfreenect2 & build it. It will generate a folder named 'freenect2'

## step2: git clone pylibfreenect2 & python stepup.py install. It will generate the python warper.

This time the opencv package from conda is not integrated with gtk. So the cv.imshow() is not working. 
I do not need opencv in this project. So I use matplotlib to do the same thing(show image). It is slower, but currently I am fine with this.

![image](https://github.com/Dearbigdog/pykinect/blob/master/camera_test/Screenshot)
