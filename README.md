🎭 AI Emotion Analyzer (Real-Time Facial Expression Recognition)

A real-time AI-powered facial emotion recognition system that detects human emotions from a live webcam feed using a Convolutional Neural Network (CNN) and displays results with emojis and confidence visualization.

This project covers the complete machine learning lifecycle:

Dataset handling

Model training

Real-time inference

Web application deployment

🚀 Features

🎥 Live webcam emotion detection

🧠 CNN-based emotion classification

🙂 Emoji-based emotion display

📊 Confidence bar visualization

🔁 Automatic emotion detection (no buttons)

👤 Face detection using Haar Cascade

🌐 Flask-based web application

🧩 Emotions Detected

😠 Angry

🤢 Disgust

😨 Fear

😄 Happy

😐 Neutral

😢 Sad

😲 Surprise

🛠️ Tech Stack
🔹 Machine Learning

TensorFlow / Keras

Convolutional Neural Networks (CNN)

Image-based FER dataset (48×48 grayscale images)

🔹 Computer Vision

OpenCV

Haar Cascade face detection

🔹 Backend

Python

Flask (REST API)

🔹 Frontend

HTML

CSS

JavaScript

Webcam API
📊 Model Training

Dataset: Image-based FER dataset

Image size: 48 × 48 grayscale

Model: CNN with Conv2D, MaxPooling, Dropout, Dense layers

Loss function: sparse_categorical_crossentropy

Optimizer: Adam

Trained using GPU (Google Colab)

▶️ How to Run the Project Locally
1️⃣ Clone the repository
git clone https://github.com/RehmanA4/AI-EMOTION-ANALYSER.git
cd AI-Emotion-Analyzer
2️⃣ Create virtual environment (recommended)
python -m venv venv
venv\Scripts\activate
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Run the Flask app
python app.py
5️⃣ Open in browser
http://127.0.0.1:5000
🧠 How It Works

Webcam captures live video frames

Flask backend receives frames as Base64 images

OpenCV detects the face using Haar Cascade

Face is resized to 48×48 and normalized

CNN model predicts emotion probabilities

Emotion + confidence is sent back to UI

UI displays emotion emoji and confidence bar

📌 Example Output

😄 Emotion: Happy

📊 Confidence: 78%

🚫 “No face detected” when face is not visible

💡 Why This Project Is Valuable

Demonstrates end-to-end ML workflow

Combines ML + CV + Web Development

Real-time inference (not static images)

Interview-ready portfolio project

Easily extensible (charts, history, deployment)
