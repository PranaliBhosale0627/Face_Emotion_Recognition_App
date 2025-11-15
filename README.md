# Face Emotion Recognition App

A real-time AI-based application that detects human emotions using a webcam. The system uses OpenCV for face detection and a CNN/DeepFace model to classify emotions such as Happy, Sad, Angry, Neutral, Surprise, and Fear.

### Features

Real-time webcam emotion detection

Uses Haar Cascade or DNN for face detection

Predicts multiple facial emotions

Lightweight and easy to run

Beginner-friendly AI + OpenCV project

### Tech Stack

Python 3.x

OpenCV

DeepFace 

NumPy

Pandas

### Installation
1️. Clone the Repository
git clone https://github.com/<your-username>/Face_Emotion_Recognition_App.git
cd Face_Emotion_Recognition_App

2️. Install Dependencies
pip install -r requirements.txt

(Optional) If using DeepFace:

pip install deepface

▶️ Run the Application
python app.py

The webcam will start automatically.

### How It Works

The webcam captures a video frame.

Haar Cascade / DNN detects the face region.

The face is preprocessed and passed to a CNN/DeepFace model.

The predicted emotion is displayed on the screen in real time.

### Example Output
Emotion: HAPPY 😀

🤝 Contributing

Pull requests are welcome. Feel free to improve the model or add new features!
