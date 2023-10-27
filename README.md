# deep-learning-projects

This is a system which can detect the drowsiness of the driver using CNN - Python, OpenCV

The aim of this is system to reduce the number of accidents on the road by detecting the drowsiness of the driver and warning them using an alarm.

Here, we used Python, OpenCV, Keras(tensorflow) to build a system that can detect features from the face of the drivers and alert them if ever they fall asleep while while driving. The system dectects the eyes and prompts if it is closed or open. If the eyes are closed for 3 seconds it will play the alarm to get the driver's attention, to stop cause its drowsy.We have build a CNN network which is trained on a dataset which can detect closed and open eyes. Then OpenCV is used to get the live fed from the camera a

To set the model up:
Pre-install all the required libraries
1) OpenCV
2) Keras
3) Numpy
4) Pandas
5) OS
Download the Dataset from the link given below and edit the address in the notebook accordingly.
Run the Jupyter Notebook and add the model name in detect_drowsiness.py file in line 20.

dataset link - (https://www.kaggle.com/datasets/dheerajperumandla/drowsiness-dataset)

The dataset which was used is a subnet of a dataset from(https://www.kaggle.com/datasets/dheerajperumandla/drowsiness-dataset)
it has 4 folder which are
1) Closed_eyes - having 726 pictures
2) Open_eyes - having 726 pictures
3) Yawn - having 725 pictures
4) no_yawn - having 723 pictures
