# AI
# NOVA AI - Voice Assistant

An intelligent voice assistant with bilingual support (English & Marathi), face recognition login, emotion detection, and web control capabilities.

## Features

- 🎤 Voice recognition in English & Marathi
- 🔊 Wake word detection — say "Hello Nova" or "नमस्कार नोव्हा"
- 😊 Emotion detection from voice tone
- 🔐 Face recognition login
- 💻 Code generation (HTML, Python, JavaScript, React)
- 🌐 Web navigation & search by voice
- 📱 App launcher (calculator, notes, calendar, drive)
- 📊 Command history stored in Firebase
- ⚡ Real-time processing with instant responses

## Tech Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js (Express) + Python (Flask)
- Auth & Storage: Firebase
- Speech: Web Speech API + Python SpeechRecognition
- Face Recognition: face-api.js

## Project Structure

```
AL/
├── index.html          # Main frontend
├── style.css           # Styles
├── script.js           # Frontend logic
├── auth.js             # Firebase authentication
├── emotionDetection.js # Emotion analysis
├── faceRecognition.js  # Face login
├── server.js           # Node.js backend
├── server.py           # Python backend
├── voice_assistant.py  # Python voice engine
├── package.json
├── requirements.txt
└── templates/
    └── index.html      # Flask template
```

## Setup

### Prerequisites
- Node.js v16+
- Python 3.8+
- A Firebase project

### Installation

1. Clone the repository and navigate to the project folder.

2. Install Node.js dependencies:
   ```bash
   npm install
   ```

3. Install Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Configure Firebase — add your Firebase config in `auth.js`.

### Running

Start the Node.js server:
```bash
npm start
```

Or start the Python server:
```bash
python server.py
```

Then open `index.html` in your browser or navigate to `http://localhost:3000`.

## Usage

1. Click **Start Listening** or enable the wake word toggle.
2. Say "Hello Nova" to activate hands-free mode.
3. Speak a command — e.g., "Open YouTube", "What's the weather?", "Write Python code for a calculator".
4. NOVA responds with voice and text output.

## Contact

- 📧 support@novaai.com
- 📱 +91 8655493832
- 📍 Mumbai, India

- website link- http://www.ai-nova.com/
