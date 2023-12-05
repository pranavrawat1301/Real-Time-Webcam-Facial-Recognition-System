# Real-Time-Webcam-Facial-Recognition-System
This project utilizes Flask, OpenCV, and face recognition to perform real-time face detection and recognition through a webcam feed. It identifies known faces and displays their names in the video stream.


# Real-time Face Recognition with Flask and OpenCV

## Overview

This project is a real-time face recognition application that utilizes Flask, OpenCV, and face_recognition to perform face detection and recognition through a webcam feed. The application identifies known faces and dynamically displays their names in the live video stream.

## Key Features

- **Webcam Integration:** Capture frames from a webcam in real-time.
- **Face Detection and Recognition:** Use OpenCV and face_recognition to detect and recognize faces.
- **Multiple Face Recognition:** Recognize multiple known faces with associated names.
- **User-Friendly Interface:** Flask-based web application with a simple and intuitive interface.
- **Stop Video Stream Button:** Allow users to stop the video stream and end the face recognition process.

## Technologies Used

- Flask
- OpenCV
- face_recognition

## Usage

1. Access the landing page to view the live webcam feed with real-time face recognition results.
2. Known faces are identified, and their names are displayed below the recognized faces.
3. Optionally, click the "Stop Video Stream" button to terminate the video feed and end the face recognition process.

## Setup and Installation

1. Clone the repository:
   
   git clone https://github.com/your-username/real-time-face-recognition.git

2. Install dependencies:

   pip install -r requirements.txt

3. Run the application:

   python app.py

4. Access the application in your web browser at [http://localhost:5000/](http://localhost:5000/).

## Project Structure

- `app.py`: Main Flask application file.
- `static/`: Static files including CSS styles.
- `templates/`: HTML templates for rendering pages.


## Acknowledgments

- Special thanks to the authors and contributors of Flask, OpenCV, and face_recognition libraries.

