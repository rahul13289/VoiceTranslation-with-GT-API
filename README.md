# VoiceTranslator-App-using-python
Create a Real Time Voice Translator using Python
In this tutorial, we're going to develop a real time voice translator using Python.

Required Modules:
Following are the libraries or modules we will need for creating the real time translator:

playsound: This module plays sounds in Python
!pip3 install playsound  
Googletrans: The "Googletrans" module can be used for free and is an unlimited Python library that implements the Google Translate API
!pip3 install googletrans  
Speech Recognition Module: It is a library which can be used by Python for recognizing the commands provided. The pip is the preferred method to perform Speech Recognition.
!pip3 install SpeechRecognition  
PyAudio: This module is used for taking the command from the user
pip install PyAudio-0.2.11-cp39-cp39-win_amd64.whl  
gTTs: The gTTs API supports various languages, such as English, Hindi, Tamil, French, German, and many more.
!pip3 install gTTs  
!pip3 install gTTS-token  
Basic Idea:

A real-time translator that can translate human language voice inputs and generates the output voice translation in the required language. It is built using Google's googleTrans API and the speech_recognition library in Python. The program will convert the texts from one language into another language and save them as an audio file in mp3 format. The playsound module will used to play the created mp3 format file. Following that, the created MP3 file is removed by using the OS module.
