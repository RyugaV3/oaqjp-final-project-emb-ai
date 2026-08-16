# Watson Emotion Detection Flask App

A Python and Flask web application that analyzes text using the **Watson NLP Emotion Predict service** and identifies the dominant emotion expressed by the user.

This project was completed as the final project for **Developing AI Applications with Python and Flask**, part of the **IBM DevOps and Software Engineering Professional Certificate** on Coursera.

## Features

- Detects anger, disgust, fear, joy, and sadness from text
- Identifies the dominant emotion
- Integrates Watson NLP through an API request
- Provides a Flask-based web interface
- Handles blank or invalid input
- Includes unit testing and static code analysis with PyLint

## Application Preview

<img width="850" alt="6b_deployment_test png" src="https://github.com/user-attachments/assets/f1f1ceff-8585-40e7-bba2-73ff2b62b439" />
<img width="850" alt="7c_error_handling_interface png" src="https://github.com/user-attachments/assets/5d8af7a5-d0c1-4b70-80f5-c494ce2526fc" />

## Technologies

- Python
- Flask
- Watson NLP
- Requests
- unittest
- PyLint
- HTML & JavaScript

## Project Structure

    EmotionDetection/
    ├── __init__.py
    └── emotion_detection.py

    static/
    templates/
    server.py
    test_emotion_detection.py

## Testing

Run the unit tests with:

    python3 test_emotion_detection.py

The final `server.py` achieved a **10.00/10** PyLint score.

## Coursework Attribution

This repository originated from the course-provided starter repository. The frontend template and JavaScript were provided as starter files, while the emotion detection logic, Python packaging, unit tests, Flask integration, error handling, and static analysis were completed as part of the coursework.
