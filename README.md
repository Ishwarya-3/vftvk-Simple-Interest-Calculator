#  STABBING ACTION DETECTION IN ATM KIOSKS

We have developed a GUI to detect the abnormal activitiy of stabbing with knife inside ATM and bank premises using the State-of-The Art :YOLOV5
# ENVIRONMENT SETUP
Python(3.6.8)

Jupyter notebook
  # Requirements
!pip install CV2

!pip install SYS

!pip install NUMPY

!pip install GLOB

!pip install PIL

!pip install tkinter

!pip install tkvideo

!pip install Torch


# RUN INSTRUCTIONS

1.Install all the required libraries and Import the ATM folder in jupyter notebook

2.Run the GUI.ipynb file in jupyter notebook

3.A tkinter window pops up

![image](https://user-images.githubusercontent.com/53227455/199953814-aa23a221-23f7-4420-a2d8-8da5d2dbc682.png)

First, Perform the foreground_segmentation which uses GMM(Gaussian Mixture Model) 

  1.The output is stored in yolov5 folder 
	
Next,Perform the stabbing detection using yolov5

  2.The output is stored in yolov5/runs/detect/exp 
	
Finally, To perform optical flow implementation using Lucas Kanade method upload the output of yolov5

