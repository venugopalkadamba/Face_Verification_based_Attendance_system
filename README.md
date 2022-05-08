# Face Verification Based Attendance System
## About
In this Attendance System the attendance for students is marked using Face verification. The Faculty has the permission to take Attendance, add a student, modify student details. The Faculty can also search for attendance of a student using Multiparameter Search, by specifying the student ID, date of attendance, period of Attendance.<br>
The credentials for the Faculty are provided by the superuser who has access to the whole database. Only the superuser can update the attendance of a student.<br>
**Django** web framework was used for the development of the whole web app. **OpenCv and face_recognition API's** were used for the development of Face Recognizer. The Face Recognizer can detect multiple faces at a time and mark their attendance into Database.<br>
**Note: Python version 3.6 was used for this project. And the dlib package required for installation of face_recognition api is also uploaded.**<br>
To run the web app on your local computer, install the required libraries([requirements.txt](https://github.com/venugopalkadamba/Face_Verification_based_Attendance_system/blob/master/requirements.txt)) using the command:<br>
```python
pip3 install -r requirements.txt
``` 
<br>and run the following command in the command prompt:<br>
```python
python manage.py runserver
``` 

**To create your own credential for logging into the application**<br/>
```python
python manage.py createsuperuser
```
<br/>
After running the above command and creating the credentials, you can use the same credentials for logging in.<br/>

## Live Video of Attendance System

![alt text](https://github.com/venugopalkadamba/Face_Verification_based_Attendance_system/blob/master/Final_video.gif)
