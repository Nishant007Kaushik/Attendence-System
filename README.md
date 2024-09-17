Project Summary: Attendance System Using Face Recognition

The Attendance System using Face Recognition is an AI-driven solution that automates attendance tracking by recognizing student faces through a camera feed. This system leverages OpenCV, face_recognition, and dlib libraries to detect, recognize, and record the attendance of individuals based on stored facial data.

How It Works:
Face Capture:

First, the system captures multiple images of each student using a camera.
These images are labeled with the student’s name and stored in a directory for future reference.
Face Encoding:

The captured images are processed using the face_recognition library, which converts the faces into numerical data called "encodings."
These encodings are unique to each individual and are saved for later comparisons.
Real-Time Face Recognition:

During attendance, the system accesses a live video feed from the camera.
It detects faces in the video stream and compares them to the stored encodings.
When a match is found, the system marks the student as "present."
Attendance Logging:

Once a student's face is recognized, their name, along with the date and time, is saved into an attendance record (usually in a CSV file).
This provides a reliable way to track who attended the class.
Your Tasks in This Project:
Capture Student Data: Set up a system to capture and store face images of all students.
Face Encoding: Use the images to generate and store facial encodings.
Real-Time Face Detection: Implement real-time face detection through a live camera feed, recognizing students by comparing live faces with stored encodings.
Record Attendance: Automate the process of logging attendance by saving recognized students’ names and the corresponding time into a CSV file.
