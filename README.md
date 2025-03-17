Face Recognition Attendance System
This project leverages face recognition technology to mark attendance. It uses Python’s OpenCV library for face detection and recognition. The system is integrated with a Django web application to handle attendance data and display it on a simple web interface.

Key Features:
Face Detection and Recognition: Uses OpenCV for real-time face recognition and matches it with stored data.
Attendance Logging: Automatically marks attendance for recognized faces and saves data in a CSV file.
Web Interface: A simple web page built with Django to display attendance records.
Technologies Used:
Python
OpenCV (for face recognition)
Django (for web application)
CSV (for storing attendance data)
Setup Instructions:
Clone the repository:
bash
Copy
Edit
git clone https://github.com/<your-github-username>/Face-Recognition-Attendance.git
Install required dependencies:
bash
Copy
Edit
pip install -r requirements.txt
Run the Django server:
bash
Copy
Edit
python manage.py runserver
How to Use:
Run the project and visit the local web server (typically http://127.0.0.1:8000/).
The system will prompt for face recognition and mark attendance automatically when a recognized face is detected.
Future Improvements:
Integration with database (e.g., MySQL or SQLite) instead of CSV.
Real-time notifications for attendance updates.
Additional face recognition models for higher accuracy.
