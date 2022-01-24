This is a college project made by our group , as heading says the aim is to detect ,recognize and mark attendance by face recognition but the project has a lot more objctives:
Enrolment
Face Image Collection For DB 
Face Recognition
Confirmation by the class camera for Attendance 
Attendance Marking
 

# The following are objectives of the project:
▪ To develop a portable Smart Attendance System which is handy and self-powered.
▪ To ensure the speed of the attendance recording process is faster than the previous system which can go as fastas approximately 3 second for each student.
▪ Have enough memory space to store the database.
▪Able to recognize the face of an individual accurately based on the face database.
▪ Develop a database for the attendance management system.
▪ Allow new students or staff to store their faces in the database by using a GUI.
▪ Able to show an indication to the user whether the face- recognition process is successful or not.

# Detection
Detection is done by the help of OpenCV and Haar cascades
Face detection using Haar cascades is a machine learning based approach where a cascade function is trained with a set of input data. OpenCV already contains many pre-trained classifiers for face, eyes, smiles, etc.. Today we will be using the face classifier. You can experiment with other classifiers as well.

# Recognition
Recognition is done by LBPH recogniser

Local Binary Pattern (LBP) is a simple yet very efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number. LBPH is one of the easiest face recognition algorithms. It can represent local features in the images. It is
possible to get great results (mainly in a controlled environment). It is robust against monotonic gray scale transformations. It is provided by the OpenCV library (Open Source Computer Vision Library).

# Database module 
In Database module all the information of student who is going to enroll in the particular college or company are stored. and for analysis we can easily use this data .

#Enrollment

In this step, the student is enrolled in the student
database. General information like Name, Enrolment Number, Class, and Section is stored in the database. Along with all this information, pictures of the student's face appearing in the camera window are also stored in the student database. 

With the help of all the images stored in the student database, facial recognition can be performed for all the students are coming to attend a lecture

# Python libraries used
1.OpenCV-python
2.Numpy
3.datetime
4.face_recognition 
5. Os
6.sqlite3
7.randam

# In Future :
We would like to make this project into an App form in the future. In which this app contains the following  menu/ module : 

1) Student Database page 
2) Face Collection DB 
3) Attendance Record of Student using face recognition
4) All the Present student records in every new excel file 
5) A automated message system which is send to the student when its not present or its attendance is very low .  

