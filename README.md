# EaRL – Marty Robot Language Learning System  
### Human-Robot Interaction Project

## Project Overview

EaRL (Educational and Robotic Learner) is an interactive Human-Robot Interaction project developed using Marty the Robot. 

The system demonstrates how socially interactive robots can assist beginner language learners through multimodal engagement combining speech recognition, translation, computer vision, and expressive robotic feedback.

Marty acts as an embodied learning companion, encouraging users to practice Spanish pronunciation through real-time interaction.

---

## Learning Modes

### Voice Translation Mode
- User speaks in English
- Sentence is translated into Spanish
- Marty pronounces translation
- User repeats in Spanish
- System evaluates correctness
- Robot provides feedback through motion and LEDs

### Image Recognition Mode
- User shows an object to the camera
- Deep learning model identifies object
- Spanish translation is generated
- User pronounces Spanish term
- Marty provides corrective or celebratory feedback

---

## Technologies Used

- Python
- MartyPy
- SpeechRecognition
- Google Speech API
- Google Translate API
- OpenCV
- MobileNetV2 (TensorFlow/Keras)
- Human-Robot Interaction principles

---

## System Structure

Code/
│
├── Master.py
├── voice_input.py
└── image_input.py


---

## Installation

Install required packages:
pip install martypy SpeechRecognition opencv-python numpy tensorflow googletrans


Update Marty’s IP address inside all three files before running.

Run the system using:

python Master.py

---

## Research Contribution

This project explores:

- Socially assistive robotics
- Multimodal interaction
- Speech-based learning systems
- Educational robotics design
- Real-time embodied feedback systems

---

## Author

Raghuram Damarla  
MSc Robotics – Heriot-Watt University







