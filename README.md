# Advaith Nair Final Project


#A small Flask app that reads a piece of text and tells you what emotion it carries, anger, disgust, fear, joy, or sadness, plus which one is the strongest.

## Files

- EmotionDetection/emotion_detection.py - talks to Watson and returns the emotion scores
- server.py - the Flask app, has the /emotionDetector route
- test_emotion_detection.py - checks the function gives the right emotion for a few sample sentences
- templates/index.html and static/mywebscript.js - the web page, already provided

## How to run it

Install what you need:

pip install flask requests

Start the server:

python3 server.py

Then open localhost:5000 in your browser.

## How to test it

python3 -m unittest test_emotion_detection.py

