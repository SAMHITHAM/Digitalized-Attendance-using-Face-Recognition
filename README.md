
# Face recognition based attendance system 

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/) 

### What steps you have to follow??
- Download or clone my Repository to your device
- type `pip install -r requirements.txt` in command prompt(this will install required package for project)
- Create a subject folder for which you want to calculate attendance inside the Attendance folder.
- open `attendance.py` and `automaticAttendance.py` and remaining python files, change all the path according to your system
- Run `attendance.py` file

### Project flow & explaination
- After you run the project you have to register your face so that system can identify you, so click on register new student
- After you click a small window will pop up in that you have to enter you ID and name and then click on `Take Image` button
- After clicking `Take Image` button A camera window will pop up and it will detect your Face and take upto 50 Images(you can change the number of Image it can take) and stored in the folder named `TrainingImage`. more you give the image to system, the better it will perform while recognising the face.
- Then you have to click on `Train Image` button, It will train the model and convert all the Image into numeric format so that computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.
- It will take some time(depends on you system).
- After training model click on `Automatic Attendance` ,you have to enter the subject name and then it can fill attendace by your face using our trained model.
- it will create `.csv` file for every subject you enter and seperate every `.csv` file accoriding the subject
- You can view the attendance after clicking `View Attendance` button. It will show record in tabular format.

### Screenshots

### Simple UI
<img src='https://github.com/SAMHITHAM/Digitalized-Attendance-using-Face-Recognition/blob/main/Project%20Snap/image1.png'>

### While taking Image
<img src='https://github.com/SAMHITHAM/Digitalized-Attendance-using-Face-Recognition/blob/main/Project%20Snap/image4.png'>

## While taking Attendance
<img src='https://github.com/SAMHITHAM/Digitalized-Attendance-using-Face-Recognition/blob/main/Project%20Snap/image8.png'>

## Attendance in tabular format 
<img src='https://github.com/SAMHITHAM/Digitalized-Attendance-using-Face-Recognition/blob/main/Project%20Snap/image7.png'>

