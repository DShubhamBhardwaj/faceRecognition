
# Face Recognition

This project demonstrates a face unlock feature using OpenCV. The application captures an image of the user's face, detects and encodes facial features, and then compares these features to a stored database to authenticate the user. The project showcases basic and advanced concepts of computer vision and machine learning.




## Features

- Face detection using Haar Cascades
- Face encoding using deep learning models
- Face recognition for user authentication
- User interface for capturing and authenticating faces
- Access to Sample Question papers on Login


## Requirements

- Python 3.x
- OpenCV 4.x
- face_recognition
- camera

## Installation

1. Clone the repository:

```bash
git clone https://github.com/DShubhamBhardwaj/faceRecognition.git
cd faceRecognition

```

2. Create and activate a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate
```

3. Install the required packages:



```bash
pip install -r requirements.txt

```


    
## Usage/Examples

```bash
python FaceLock.py
```

1. Once the Software Windiow opens Sign up using the sign Up button and add face samples during sign up. 
2. After that you can use Face Unlock Feature to access the Question papers


## How It Works

1. Face Detection: Uses Haar Cascades to detect faces in the camera feed.
2. Face Encoding: Uses deep learning models to extract unique features from the detected face.
3. Face Recognition: Compares the encoded features with those in the database to find a match.
4. Authentication: If a match is found, the user is authenticated; otherwise, access is denied.v
## Documentation

https://opencv.org/

https://docs.python.org/3/library/tkinter.html


## How It Works

1. Face Detection: Uses Haar Cascades to detect faces in the camera feed.
2. Face Encoding: Uses deep learning models to extract unique features from the detected face.
3. Face Recognition: Compares the encoded features with those in the database to find a match.
4. Authentication: If a match is found, the user is authenticated; otherwise, access is denied.v
