Facial Recognition Program

-Special thanks to Adrian at Pyimagesearch for the tutorial on how to first begin with facial detection and recognition.

Required: Python 2.7 or later, including installations of modules:
-opencv
-imutils
-numpy
-sklearn

By default, the program uses whatever the primary camera is for the system you are running it on, usually a front facing web cam.
The program is designed to be run from the command line, but can be modified to be run from an IDE, or even a user created application.

Directions: create a directory with all files inside of it (I suggest putting it in desktop to make it easier to access from the cmd)
The Video FRA demo provides a brief demonstration of the programs functionality.

1) First you need to provide pictures of your face, so run the command

>python Your\created\directory\dfv.py --name "YourName" 

press 'f' a few times to capture a few images of your face, then press 'q' when you are finished.

2) Next you need to update the database and train the model

>python ....\update.py

3) Test program's recognition of the face

>python .....\RV.py