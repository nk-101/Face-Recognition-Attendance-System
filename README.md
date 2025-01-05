# Face-Recognition-Attendance-System
This project is a Python-based facial recognition system that captures and logs the attendance of known individuals using a webcam. It detects faces in real-time, matches them with pre-stored face encodings, and records their attendance in a CSV file with the date and time of arrival.

Features:
Real-time face recognition using the face_recognition library.
Records attendance of known faces by comparing them with pre-stored face encodings.
Logs the name and the exact time a person is detected.
Generates a CSV file with the date as the filename for easy attendance tracking.
Displays the name and "Present" label on the live video feed when a person is recognized.

Requirements:
Python 3.x
face_recognition library (pip install face_recognition)
opencv-python library (pip install opencv-python)
numpy library (pip install numpy)
csv (Python standard library)

How to Use:
Ensure you have images of the people whose faces you want to recognize (e.g., "nidhi.jpg", "jethalal.png") stored in the faces directory.
Run the script. It will open a video feed from the webcam.
When a recognized face is detected, it will print their name and "Present" on the screen.
The attendance is logged in a CSV file named with the current date (e.g., 2025-01-05.csv) containing the names and times of detected individuals.
To stop the program, press the "q" key.

Example:
Input: "Nidhi" detected
Output:
Video Feed: "Nidhi Present"
CSV Log: "Nidhi", "2025-01-05 12:30:45"
