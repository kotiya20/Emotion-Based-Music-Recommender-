The Emotion-Based Music Recommender is a web application that recommends songs based on the user’s emotions, detected via facial expressions. It uses computer vision to capture real-time facial images and a deep learning model to classify the emotions. Based on the detected emotion, the app provides music recommendations to match the user's current mood.

Features
Emotion Detection: Real-time emotion detection using the webcam.
Music Recommendation: Personalized song suggestions based on the detected emotion.
AI-Powered: Utilizes MediaPipe for face detection and Keras for emotion classification.
Web-Based Interface: Interactive web application for user convenience.
Seamless Integration: Music recommendations pulled from online sources or preloaded playlists.

Tech Stack
Frontend: Streamlit (for creating the web interface).
Backend:
Python (for server-side logic and model integration).
OpenCV (for real-time facial capture).
MediaPipe (for face detection).
Keras (for emotion recognition using a CNN model).
Machine Learning Model: Convolutional Neural Network (CNN) trained on a facial emotion dataset.

Libraries:
Streamlit
Streamlit-webrtc
OpenCV
TensorFlow/Keras
MediaPipe
Pandas, NumPy
