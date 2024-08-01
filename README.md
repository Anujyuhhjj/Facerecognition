# Real-Time Face Verification with OpenCV and DeepFace
This project captures video from a webcam, periodically checks if a face in the current frame matches a reference image, and displays the result on the video feed in real-time. It uses OpenCV for video capture and image processing, and DeepFace for facial recognition.

## Features
- Real-time video capture from webcam
- Periodic face verification against a reference image
- Visual indication of face match on the video feed
- Multithreaded face verification to maintain smooth video playback

## Requirements
- Python 3.x
- OpenCV
- DeepFace

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/face-verification.git
    cd face-verification
    ```

2. Install the required libraries:
    ```bash
    pip install opencv-python-headless
    pip install deepface
    ```

3. Place your reference image in the project directory and name it `image.jpg`.

## Usage
Run the script:
```bash
python face_verification.py
