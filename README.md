# 💬 GRizzApp

RizzApp is a web-based chatbot experience that uses the **Google Gemini API** to evaluate and interact with users based on their "Rizz" — a playful metric of charisma and charm.

The app responds to the user's messages with personality, dynamically updating a "Rizz Meter" to reflect how smooth, funny, confident, or flirty the conversation is. Customize the AI's personality in real-time to be:
- ✨ **Friendly**
- 🔥 **Flirty**
- 😂 **Funny**
- 💪 **Confident**
- 💪 **Authoritative**


## 🛠️ Features

- 🎯 Real-time personality adjustment
- 📈 Dynamic Rizz meter with a responsive slider UI
- 🤖 Gemini-powered generative conversation
- 🧠 Lightweight async backend with `aiohttp`


## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/ChrisBastajian/RizzApp.git
cd RizzApp
```

### 2. Set Up the Environment

Make sure you have Python 3.9+ installed. Then install dependencies:

```bash
pip install -r requirements.txt
```

Create a .env file and add your Google Gemini API key:

```
GOOGLE_API_KEY=your_api_key_here
```

### 3. Run the App Locally

```
python main.py
```

Once the server is running, open your browser and go to:

```
http://127.0.0.1:8080/
```

## 📦 requirements.txt
```
aiohttp>=3.8.0
python-dotenv>=1.0.0
google-generativeai>=0.3.2
```

## 🧠 Future Improvements

- User authentication

- Save Rizz history across sessions

- Enhanced UI/UX with animations

- More personality modes and deeper dialog states

## 🧃 What is Rizz?

"Rizz" is modern slang for charisma — your ability to charm, flirt, or impress in a conversation. RizzApp gives you a fun, interactive way to test and build that charm with an AI who judges you accordingly.
