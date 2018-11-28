Traffic Sign Classifier modification for mexican traffic sign.


Description 
This classfier is a modified version of an existing classifier. The difference is that now it is able to 
correcly identify mexican traffic signs. The model is trained using a SVM model and traffic sign pictures.
In order to increase the acurracy of identified signs hundreds of photos were taken of mexican traffic signals. 


Dependencies
Python 3.5
OpenCV3
Imutils (usepip3 install imutils to install)

System structure
There are three .py files that run the program
1.-main.py
2.-classification.py
3.-common.py
In the root file is a file named dataset. This file contains all the pictures taken in order for the trianing to 
work for mexican signals
There are also 4 video examples that can be used to test run the program.
Two outputs of the program have also been added so that the user can see the results. 

data_svm.dat : Saved SVM model after training.
README.txt

How to run 
Download the repository using git bash
Open anacondaprompt or the command promt
Get into the root folder using de cd command
When you are inside the folder you can either run the program without inputing a video to only train the data.svm or
you can train and run the video. The structure to run it is the following
python main.py --file_name YOURFILE

Future development
More than one traffic sign identification. 