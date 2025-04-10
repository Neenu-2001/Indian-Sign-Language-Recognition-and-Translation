# Indian-Sign-Language-Recognition-and-Translation
Gesture Genie is a sign language project for Indian Sign Language (ISL) recognition and translation. It uses an InceptionV3 CNN model with OpenCV for real-time gesture detection and a Django backend for processing. It also includes speech-to-sign translation using the Google Speech API to support better communication.

✨ Features

- 🔤 ISL letters and word recognition
- 🖐️ Real-time hand gesture detection using OpenCV
- 🧠 Gesture classification with InceptionV3 CNN
- 🗣️ Speech-to-sign translation with Google Speech API
- 🌐 Django backend for smooth integration and processing


  🛠️ Technologies Used

- Python
- Django
- TensorFlow / Keras
- OpenCV
- PIL
- Google Speech Recognition API

See requirements.txt for versions and required packages

To create a new app within a Django project, you can use the following command:
python manage.py startapp app_name

Replace app_name with the desired name of your app.

Don’t forget:
After creating the app, add it to the INSTALLED_APPS list in your project’s settings.py:

INSTALLED_APPS = [
    ...
    'recognition',
]


Run the Django server:
python manage.py runserver

