Face-Recognition-attendance-system



Author - KEERTAN

About the Project:



This is a real-time face recognition attendance system that captures a user's face using a webcam, verifies it against stored images, and logs attendance with a timestamp. It integrates OpenCV, face_recognition, and NumPy for efficient processing.



✨ Features:



Face Recognition using pre-stored images

Automatic Attendance Marking in a CSV file

Real-Time Detection via webcam

User Identification with name display

Simple & Fast Execution

🛠 Technologies Used:



Python

OpenCV (for image processing)

face_recognition (for facial recognition)

NumPy (for numerical operations)

CSV Handling (for attendance tracking)

`Project Structure:



Face Recognition Attendance System



│-- 📂 known_images/ # Folder containing images of registered users



│-- 📄 attendance_system.py # Main Python script



│-- 📄 attendance_sheet.csv # Logs attendance records



│-- 📜 README.md # Project Documentation



`How to Run the Project:



🔹 Prerequisites



Ensure you have Python installed and install required libraries:



pip install OpenCV-python face-recognition numpy



🔹 Run the Code:



python attendance_system.py



The webcam will open and start recognizing faces!



How Attendance Works:



The program captures real-time video from the webcam.

It compares detected faces with stored images in the known_images folder.

If a match is found, it logs attendance with a timestamp in attendance_sheet.csv.

If no match is found, it displays "Unknown" and does not mark attendance.

Sample Output:



✅ Recognized Face



John Doe recognized at 2025-03-21 10:15:30



Unrecognized Face



Unknown detected. No attendance marked.



`Future Improvements:



GUI Integration using Tkinter or PyQt

Database Storage instead of CSV

Multiple Camera Support

Face Mask Detection

🤝 Contributing:



Want to improve this project? Fork the repo and submit a pull request!
