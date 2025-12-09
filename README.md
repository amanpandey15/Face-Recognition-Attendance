# Face Recognition Using Flask
# Real-Time Face Recognition Attendance System (Flask + Python)

## Overview
This is a Flask-based web application that detects and recognizes faces in real time using OpenCV and the `face-recognition` library, 
and automatically logs attendance in CSV format. It is designed for educational purposes and includes custom enhancements for a more professional and feature-rich experience.

## Features
- Live face detection & recognition
- Automatic CSV attendance logging with date & time
- Prevents duplicate entries in the same session
- Face registration module for adding new users dynamically
- Daily summary report generation
- Simple, responsive web interface

## Technologies Used
- Python 3.x
- Flask
- OpenCV
- face-recognition
- Pandas
- NumPy
- HTML, CSS

## Installation
```

# Navigate to project folder
cd face-recognition-attendance

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

## Usage
1. Run the application using `python app.py`.
2. Open the browser and go to `http://127.0.0.1:5000`.
3. Register new faces through the admin interface.
4. Start live recognition to mark attendance automatically.
5. Check the daily summary report generated in the Attendance folder.

## Project Structure
```
/Attendance         # Stores attendance CSV files
/static/faces       # Stores registered face images
/templates          # HTML templates
app.py              # Main application file
requirements.txt    # List of dependencies
README.md           # Project documentation
```

## Screenshots
*<img width="515" height="462" alt="Sample Screenshot 1" src="https://github.com/user-attachments/assets/a621e258-af8b-44b9-8408-8482575c3d97" />
*

## Author
This project was developed for learning purposes, inspired by open-source face recognition projects, and enhanced with additional features.
