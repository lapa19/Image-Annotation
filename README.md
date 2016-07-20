# Image-Annotation
This is an image annotation application developed with OpenCV's python interface. Its GUI was designed with PyQt.
The monumentsdb folder is the database where we have pictures of certain monuments against which we compare the user input image. 
The popgui.py file contains the main code.
The popsift.py contains code for using OpenCV's inbuilt SIFT algorithm.
writekp.py contains code to store keypoints of each of the images in monumentsdb in a file.
These keypoints are stored in the monuments.pkl file from which they are later read during program execution.Instead of finding keypoints during each execution,we've stored them to a file to save execution time.
By clicking on the popgui.exe icon,one can run the application.
