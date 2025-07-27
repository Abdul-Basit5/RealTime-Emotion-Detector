<h1>😊 Real-Time Face Emotion Recognition Using Machine Learning</h1>

<h2>📌 Overview</h2>
<p>This machine learning project detects and classifies human facial emotions in real-time using webcam input. It utilizes Convolutional Neural Networks (CNN) and OpenCV to capture live facial expressions and recognize emotions like Happy, Sad, Angry, and Neutral.</p>

<h2><strong>🧠 Techniques Used</strong></h2>
<p><strong>• Computer Vision:</strong> Face detection using OpenCV Haar Cascade</p>
<p><strong>• Deep Learning:</strong> Emotion classification using CNN</p>
<p><strong>• Real-Time Processing:</strong> Live video stream handling with OpenCV</p>

<h2><strong>🚀 Models Implemented</strong></h2>
<p><strong>• Convolutional Neural Network (CNN)</strong></p>
<p><strong>• OpenCV Haar Cascade Classifier for face detection</strong></p>

<h2>🛠 Installation</h2>
<p>Make sure Python is installed, then install the required libraries:</p>
<code>pip install opencv-python tensorflow numpy</code>

<h2>📂 Dataset</h2>
<p>The project uses the <strong>FER2013</strong> dataset (Facial Expression Recognition), which contains labeled grayscale images of faces representing different emotions.</p>

<h2>🔥 Steps Performed</h2>
<ul>
    <li>Preprocess facial expression images (resize, normalize)</li>
    <li>Train CNN model on FER2013 dataset</li>
    <li>Load the trained model</li>
    <li>Capture live video from webcam</li>
    <li>Detect face and classify emotion in real-time</li>
    <li>Display emotion label on video feed</li>
</ul>

<h2>▶ Usage</h2>
<p>Run the main Python script using:</p>
<code>python emotion_recognition.py</code>
<p>Ensure the trained model file (.h5) is available in the same directory.</p>

<h2>📈 Results</h2>
<p>Accurately detects and classifies emotions from real-time webcam video, providing an interactive and intelligent facial emotion recognition experience. Ideal for mental health analysis, AI-enhanced interaction systems, or emotion-based applications.</p>
