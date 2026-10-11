# Emotion Detector

An AI-powered web application that analyzes user text inputs using the Watson NLP library to detect specific emotions (anger, disgust, fear, joy, and sadness) and identify the dominant emotion.

## Features
- **Emotion Analysis:** Integrates with Watson NLP to score text across multiple emotion metrics.
- **Dominant Emotion Detection:** Automatically calculates and highlights the primary emotion detected.
- **Flask Web Interface:** Provides an interactive web UI for users to analyze text in real-time.
- **Robust Error Handling:** Handles blank inputs and API error responses gracefully.
- **Tested & Linted:** Includes a full suite of unit tests and adheres to PEP8 code quality standards.

## Project Structure
- `EmotionDetection/`: Core package containing the emotion detection logic.
- `static/` & `templates/`: Frontend assets and HTML templates for the Flask application.
- `server.py`: Flask web server entry point.
- `test_emotion_detection.py`: Unit tests for validating application logic.
