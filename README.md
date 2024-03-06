# Emotion based music recommendation system
## About
The primary objective of our project is to design and implement an emotion recognition system that seamlessly integrates with existing music recommendation algorithms. We aspire to enhance the user experience by dynamically adjusting song recommendations based on the real-time analysis of facial expressions. The scope of our project encompasses the development of a robust and efficient system capable of accurately identifying a spectrum of emotions and translating this understanding into tailored music suggestions.
## Methodology
### 3.1 Approach or Methodology
Our methodology for developing the "Emotion Recognition for Song Recommendation" system involves a multi-step process that seamlessly integrates computer vision techniques for emotion detection with existing music recommendation algorithms. The workflow can be summarized as follows:

3.1.1 Face Detection using Haar Cascade Classifier
We begin by leveraging the Haar Cascade Classifier, a machine learning-based approach for object detection, specifically faces. The OpenCV library provides a pre-trained face cascade model that allows us to identify and extract facial regions from the input video stream. This initial step forms the foundation for subsequent emotion analysis.

3.1.2 Emotion Analysis using DeepFace Library
Once faces are detected, the DeepFace library comes into play for emotion analysis. DeepFace utilizes pre-trained deep learning models to recognize a variety of facial expressions, including happiness, sadness, anger, surprise, and more. The system analyzes the facial features captured by the Haar Cascade Classifier and determines the dominant emotion in real-time. The resulting emotion labels are then used to inform the song recommendation process.

### 3.2 Tools, Technologies, and Languages
Our project relies on a combination of open-source libraries and programming languages to implement the proposed methodology:

OpenCV: The Open Source Computer Vision library is used for face detection through the Haar Cascade Classifier.

DeepFace Library: A deep learning-based facial analysis library that provides pre-trained models for emotion recognition.

Python: The project is implemented using the Python programming language, providing a versatile and efficient environment for computer vision and machine learning tasks.
## How to Install and Run the Project
1. Install [Anaconda Navigator](https://www.anaconda.com/download)
2. Run Jupyter Notebook
