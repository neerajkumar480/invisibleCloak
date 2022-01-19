# invisibleCloak
This project was inspired from the all time favourite "Harry Potter" in which Harry receives a invisible cloak which upon covering hides the things.
I have used openCv to develop the project with the help of python

steps to run the project
1)Downlaod the project zip folder
  After unzipping you will find 2 files i.e invisibleCloak.py and requirement.bat
2)Move all the files to your working directory and run the requirement.bat
  OpenCv will be installed, if previously installed it will show requiremnt satisfied(basically it's a batch file for windows which fires a pip install command)
3)Now run invisibleCloak.py using python  interpreter (>3.6)
4)If all ok your system's inbuilt cam will be initialized
5)Initially you have to just allow the window to capture your background for 2,3 seconds mind it only background not anything else.
6)Now you may come to the frame with a cloak/cloth/objects/anything of colour "RED" the frame will hide the cloak/cloth/objects/anything.
7)When you are done with the demo for quitting press 'q' (Without '')

Horray now you can hide anything you want by covering it with RED cloth or any object with colour red.

Note:If you are using external webcam then you have to specify VideoCapture(1) to intimate the program which camera to use in my case i had an inbuit system cam so i have given 0 as argument.

Thank You
