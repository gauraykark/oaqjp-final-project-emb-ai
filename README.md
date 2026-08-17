# Final Project: Emotion Detection Application

A web-based emotion detection application built using Python, Flask, and IBM Watson NLP runtime services.

## Overview
This application analyzes user-provided text to evaluate emotional tone and score five key emotions:
- **Anger**
- **Disgust**
- **Fear**
- **Joy**
- **Sadness**

It also identifies and displays the **dominant emotion** from the input text.

## Features
- **Emotion Analysis Engine:** Powered by Watson NLP Embed API (`emotion_aggregated-workflow_lang_en_stock`).
- **Flask Web Server:** Serves an interactive HTML interface and REST API endpoints.
- **Robust Error Handling:** Properly handles status code `400` and blank/invalid inputs gracefully.
- **Unit Tested:** Built with Python `unittest` framework ensuring reliable classification.
- **Static Code Analysis:** Formatted and styled following PyLint compliance.

## Project Structure
```text
.
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── server.py
├── test_emotion_detection.py
└── README.md
