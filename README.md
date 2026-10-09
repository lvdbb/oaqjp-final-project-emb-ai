# Emotion Detector

Final project: an AI-based web application that detects emotions (anger, disgust,
fear, joy, sadness) in text using the Watson NLP EmotionPredict service, deployed
with Flask.

## Project structure

- `EmotionDetection/` - package containing the `emotion_detector` function
- `server.py` - Flask web application
- `test_emotion_detection.py` - unit tests
- `templates/`, `static/` - web interface

## Run

```bash
python3.11 server.py
```

Then open http://localhost:5000
