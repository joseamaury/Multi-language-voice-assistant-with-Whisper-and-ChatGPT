# 🎙️ AI Voice Assistant API

A complete voice assistant that captures audio, transcribes, processes with AI, and responds in voice — all end-to-end.

---


## 📌 About the Project

This project implements an intelligent voice assistant using modern technologies for audio capture, speech recognition, and artificial intelligence.

The solution allows the user to:

🎤 Speak directly in the browser
🧠 Have their speech transcribed with AI
💬 Receive an intelligent response from ChatGPT
🔊 Hear the response converted into voice

All of this in a fluid and automated way.

---


## 🧠 Solution Architecture

The project was divided into four main stages:

---


### 1️⃣ Audio Capture (Frontend + Backend)
Use of Web API MediaDevices (JavaScript)
Real-time audio capture in the browser
Sending the audio to the Python backend
Storage and preparation of the file for processing

---


### 2️⃣ Speech Recognition (Whisper)
Use of the Whisper model
Accurate transcription of audio into text
Support for multiple languages
High robustness for different accents and noise

---


### 3️⃣ Integration with AI (ChatGPT)
Sending the transcribed text to the ChatGPT API
Processing the request using natural language
Generation of intelligent and contextual responses

---


### 4️⃣ Text-to-Speech Conversion (gTTS)
Use of the gTTS (Google Text-to-Speech) library
Conversion of the response into audio
Configuration of language and speech speed
Returning the spoken response to the user

---


## 🔄 Application Flow

id="flow"
User speaks 🎤
↓
Audio captured (JS)
↓
Python backend receives
↓
Whisper transcribes 🧠
↓
ChatGPT processes 💬
↓
gTTS generates voice 🔊
↓
Response returns to the user


---


🛠️ Technologies Used
🔹 Backend
Python 🐍
Whisper (OpenAI)
gTTS
FastAPI / Flask (adjust according to your case)

🔹 Frontend
JavaScript
Web API MediaDevices

🔹 AI
ChatGPT API

---


## ⚙️ Features
✅ Audio capture via browser
✅ Automatic speech transcription
✅ AI-powered processing
✅ Intelligent text response
✅ Text-to-speech conversion
✅ Complete virtual assistant experience

---


## ▶️ How to Run the Project

Simply open the provided Google Colab link, and good luck :)
https://colab.research.google.com/drive/1x21L3L86Fe_UWu6DUBmqx1HfR9pCovEg#scrollTo=xVJe979lA_8D

---


## 🧪 How to Test

Open the https://colab.research.google.com/drive/1x21L3L86Fe_UWu6DUBmqx1HfR9pCovEg#scrollTo=xVJe979lA_8D in the browser
Allow microphone access
Record your voice
Wait for processing
Listen to the generated response

---


## 📊 Project Structure

📁 project/
├── frontend/
│ └── audio_capture.js
├── backend/
│ ├── main.py
│ ├── whisper_service.py
│ ├── chatgpt_service.py
│ └── tts_service.py
├── audio/
├── requirements.txt
└── README.md

---


## 🔒 Security and Best Practices

Input validation
Separation of responsibilities (services)
Scalable modular structure
Prepared for future authentication

---


👨‍💻 Author

José Amaury
📧 amaury345.ja@gmail.com

🔗 https://www.linkedin.com/in/joseamaury

🐙 https://github.com/joseamaury
