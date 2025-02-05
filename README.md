# Face-Recognition-System
# Face Detection and Recognition System

## Overview
The Face Detection and Recognition System is a Python-based application using OpenCV and Tkinter for GUI. It captures, trains, and recognizes faces using Local Binary Patterns Histograms (LBPH) face recognition algorithm. It also integrates MySQL for storing user details.

## Features
- **Face Data Collection:** Capture face images and store them.
- **Face Training:** Train the model using collected data.
- **Face Detection & Recognition:** Recognize faces in real-time.
- **GUI Interface:** User-friendly interface using Tkinter.
- **Database Integration:** Store user information in MySQL.

## Technologies Used
- **Python**
- **Tkinter (GUI)**
- **OpenCV** (cv2)
- **NumPy**
- **Pillow (PIL)**
- **MySQL (pymysql)**

## Installation

### Prerequisites
- Install Python (>=3.6)
- Install MySQL and create a database

### Dependencies
Run the following command to install required libraries:
```sh
pip install opencv-python numpy pillow pymysql
```

### Database Setup
1. Create a MySQL database named `autherized_user`.
2. Create a table `Known_person` with columns `id (INT)`, `Name (VARCHAR)`, `Age (INT)`, `Address (VARCHAR)`.

### Running the Application
Run the script using:
```sh
python face_recognition.py
```

## Usage
1. **Enter User Details:** Provide Name, Age, and Address.
2. **Generate Dataset:** Capture images and store them.
3. **Train Classifier:** Train the model using the collected dataset.
4. **Detect Faces:** Recognize faces using the trained model.

## Project Structure
```
face-detection/
│-- data/                     # Folder for storing captured images
│-- haarcascade_frontalface_default.xml # Face detection model
│-- classifier.xml             # Trained classifier
│-- face_recognition.py        # Main script
│-- README.md                  # Project documentation
```

## Future Enhancements
- Add emotion detection
- Implement multi-face recognition
- Improve UI and add more functionalities

## Author
Developed by **Lokesh Kumar** - Face Recognition System ©2024

