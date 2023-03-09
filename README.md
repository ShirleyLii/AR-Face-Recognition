# Face-Recognition-With-OpenCV

## Please email me at shirley_li94@hotmail.com for the access to new private repository link https://github.com/ShirleyLii/Face-Recognition-with-OpenCV-and-Python (this project)! Thank you!! 

[![python3.6](https://img.shields.io/badge/python-3.6-brightgreen.svg)]()

Recently Image recogntion has joined forces with another cutting-edge technology - augmented reality - to create an entire differnt world that provides both an entertaining and commercial value.

A lot of people have really bad memories and they just could not remember a new face. It is really awkward that when someone is waiving at you at the end of the hallway and calling your name, but you just could not remember his/her name. What if there's an App which could help you to jog your memory?  
This is a project which combines Augmented Reality and Image Recognition.    


[![python3.6](https://img.shields.io/badge/python-3.6-brightgreen.svg)]()

Have you noticed that every time when you upload a photo to Facebook, the platform has developed an ability to recognize you and your frirends in the photo? Back in days, Facebook used to ask YOU to tag yourself or your friends in the photos by clicking on your face or your friends' then typing in the names. But now, the plantform uses facial recognition algorithms to identify the people in that image and automatically tags everyone with high accuarcy for you. It is a raelly amazing technology with 98% accuracy which is pretty much as good as humans can do. 

:+1: So this project aims at self learning Computer Vision, OpenCV, Python, Deep Learning and most importaly how modern face recognition works!

## Project Features
- [x] Real time Image Processing on Webcam
- [x] Facial Detection on an image    
- [x] Facial Detection on webcam    
- [x] Facial Identification via OpenCV
- [x] Display right image information and related person's name

![](shirleyDetect.gif)
![](DetectSample2.gif)

## Requriments: 
Mac or Windows with a built-in webcam 
> Camera-test.py file is provided to test if your webcam is working or not

Python3 (3.6++ is recommended)

Homebrew 
```
$ brew install wget
```
Tap homebrew-bio
```
$ brew tap brewsci/bio
```

## Dependencies: 
1. Install OpenCV (real time image processing)  
```
$ brew install opencv4
```
2. Change into the OpenCV directory
```
$ brew list
```
Go into the opencv directory
```
$ cd /usr/local/Cellar/opencv/4.1.0_1
$ pwd
/user/local/Cellar/opencv/4.1.0_1
```

3. Find the  cv2.<version>.so file in OpenCV
Firstly check and make sure your Python is the latest version
```
$python --version
Python 3.7.0
```
Then get the Python 3.7.0 cv2.<version>.so File Path
```
# cd /usr/local/Cellar/opencv/4.1.0_1/lib
...
python3.6 
...
...
$ cd python3.7.0
$ cd site-packages
$ pwd
/usr/local/Cellar/opencv/4.1.0_1/lib/python3.7.0/site-packages
$ ls
cv2.so
```
Test if you have installed OpenCV successfully 
```
$ python3
>>> import cv2
>>> print(cv2.__version__)
4.1.0 
```
Numpy  (This will be installed when you do command $brew install opencv4)

Tensorflow


## How To Run the Project
1. Firstly go to the src file and run the training model file face-train.py.
```
$ cd src
$ python3 face-train.py
```
- This process will train all the images in data directory
- It will also train the facial recognizer and save it to a trainer.yml

2. Secondly run the face recognition main program face.py.
```
$ python3 face.py
```
- After training the facial recognizer and save it to trainer.yml as the step above, face.py is the place to implement recognizer and trained data
- With trained data, we run recognization predictions on the items here. 


## What to Improve for the Future
* Gather more training data
* Improve and implement more models to campare and get a higher accuracy
* Maybe add more Snapchat like filters


