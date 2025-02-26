# Real-Time-Speech-to-Text-AI
This project implements a real-time speech-to-text system that transcribes spoken words into text and interacts with an AI model to generate intelligent responses. It also converts AI-generated text back into speech, creating a complete voice-based conversational loop.

## Key Features
Speech Recognition: Converts spoken words into text using the speech_recognition library. 

AI-Powered Responses: Integrates Grok AI to analyze and generate meaningful replies based on transcribed text.

Text-to-Speech Conversion: Converts AI-generated responses back into speech for seamless interaction.

Real-Time Processing: Listens to audio input, processes it instantly, and provides spoken AI-generated responses.

Error Handling: Implements noise adjustment, exception handling, and API request management for smooth execution.

## Workflow

Speech-to-Text: The microphone captures speech and converts it into text.

AI Processing: The transcribed text is sent to Grok AI, which generates a response.

Text-to-Speech: The AI response is converted back into speech for real-time interaction.

Continuous Loop: The system keeps listening and responding until the user exits.

## Technologies Used

Python (speech_recognition, pyttsx3, requests)

Grok AI for text-based responses

Google Web Speech API for speech recognition

## How to Use

Run the script and start speaking.

The system will recognize your speech and send it to Grok AI.

AI-generated responses will be spoken back to you.

Say "exit" to stop the program.
