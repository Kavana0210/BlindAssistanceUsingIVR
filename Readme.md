Object Detection and Image Text-to-Speech Assistant
This project uses a combination of computer vision, text recognition, and text-to-speech technologies to build two main functionalities:
1. Real-Time Object Detection with Audio Feedback
2. Image-to-Text Conversion with Audio Playback

Features
1. Real-Time Object Detection (code1.py)
Utilizes OpenCV's DNN module with a pre-trained SSD MobileNet model.
Detects objects in real-time from a webcam feed.
Converts detected object labels into speech using pyttsx3.

2. Image Text-to-Speech (readimg.py)
Captures an image using webcam.
Extracts text from the image using easyocr.
Converts extracted text to speech using pyttsx3.

Requirements
Python 3.x
OpenCV (cv2)
PyTTSX3 (pyttsx3)
EasyOCR (easyocr)
PIL (pillow)
Matplotlib

Install them using:
pip install opencv-python pyttsx3 easyocr pillow matplotlib

How to Run
Object Detection:
python code1.py
A window will open showing webcam feed.
Detected objects will be outlined and spoken aloud.
Image Text-to-Speech:
python readimg.py
Captures an image from webcam.
Extracts visible text and speaks it aloud.

Applications
Assisting visually impaired users in understanding their surroundings.
Basic OCR-based document reader.
Real-time object monitoring.
