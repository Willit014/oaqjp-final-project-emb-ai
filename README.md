# Final Project – AI-Based Emotion Detection Web App

This project was developed as part of the **"Developing AI Applications with Python and Flask"** course.

## 🔍 Objective

To build a Flask-based web application that detects emotions in customer feedback using the Watson NLP `EmotionPredict` API.

## 📦 Structure

final_project/
├── EmotionDetection/
│ ├── init.py
│ └── emotion_detection.py
├── test_emotion_detection.py
├── server.py


## 🧠 Main Features

- Uses **Watson NLP API** to detect emotions (joy, anger, fear, sadness, disgust).
- Returns a dictionary of scores and the dominant emotion.
- Includes error handling for empty input or invalid requests.
- Fully tested with `unittest`.
- Deployed with **Flask** at `http://127.0.0.1:5000/emotionDetector?text=...`.
- Fully PEP8-compliant (10/10 from `pylint`).

## 🧪 Sample Output

Input:


Output:

```json
{
  "result": "For the given statement, the system response is 'anger': 0.0012, 'disgust': 0.0005, 'fear': 0.0023, 'joy': 0.9756 and 'sadness': 0.0204. The dominant emotion is joy."
}

