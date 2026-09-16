# Emotion Detector

Final project for the IBM Skills Network course. The Flask application sends
English text to the Watson NLP emotion service and reports scores for anger,
disgust, fear, joy, and sadness together with the dominant emotion.

## Run locally

```bash
python -m pip install -r requirements.txt
python server.py
```

Open `http://localhost:5000` in a browser.

## Run the unit tests

```bash
python -m unittest test_emotion_detection.py
```
