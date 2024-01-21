# Face Recognition Based Attendance System

This project is a face recognition-based attendance system that uses OpenCV and Python. The system uses a camera to capture images of individuals and then compares them with the images in the database to mark attendance.

## Installation

1. Clone the repository to your local machine. ``` git clone https://github.com/Quang1129/Face_attendance-ESP32-CAM ```
2. Install the required packages using ```pip install -r requirements.txt```.
3. Download the dlib models from https://drive.google.com/drive/u/0/folders/1Gelci-6v9ykAsWp7sGZLxcqlBb8aHUVk and place the data folder inside the repo

## Usage

1. Collect the Faces Dataset by running ``` python get_faces_from_camera_tkinter.py``` .
2. Convert the dataset into ```python features_extraction_to_csv.py```.
3. To take the attendance run ```python attendance_taker.py``` .
4. Check the Database by ```python app.py```.


## Contribution

1. Phan Nhat Quang
2. Tran Van Dat
3. Phan Van Quy



