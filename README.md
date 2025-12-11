# Hand Sign Language Translation — Web App

A simple Flask-based application that detects hand landmarks from a live webcam feed and predicts hand signs using a scikit-learn model. Includes basic routes, HTML templates, and SQLite persistence.

## Tech Stack
- **Backend:** Python, Flask
- **CV/ML:** OpenCV, MediaPipe, scikit-learn (RandomForest model loaded from `.pkl`)
- **Storage:** SQLite
- **Frontend:** HTML templates (Jinja2)
- **Utilities:** gTTS/pyttsx3 (optional TTS), logging

## Features
- Live webcam video feed  
- Hand landmark extraction (MediaPipe)  
- Model-based prediction of hand signs  
- Login/Register/Admin templates  
- Optional text-to-speech & translation  

## Project Structure

## Setup

## Run the App

## Notes
- Database (.db), CSV, and model (.pkl) files are intentionally not included.
- These files are ignored through `.gitignore`.

## License
MIT
