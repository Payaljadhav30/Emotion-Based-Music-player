
# 🎵 Emotion-Based Music Player

An AI-powered music player that analyzes your **text input** to detect emotions and automatically generates personalized **Spotify playlists** based on your mood.

---

## 🚀 Features
- 🎭 **Emotion Detection:** Uses NLP to identify emotions from user text (happy, sad, relaxed, etc.)
- 🎧 **Spotify Integration:** Fetches real-time playlists from Spotify based on detected mood
- 🔄 **Dynamic Playlist Generation:** Generates unique playlists even for similar inputs
- ⚡ **Fast & Lightweight:** Built using Flask and Python APIs
- 🔒 **Environment Protected:** Uses `.env` for secure API key handling

---

## 🛠️ Tech Stack
| Category | Technologies |
|-----------|--------------|
| Backend | Flask, Python |
| AI/NLP | Transformers, Torch |
| API Integration | Spotify API, Ollama API |
| Deployment | Docker, Gunicorn |
| Others | Flask-CORS, python-dotenv |

---

## ⚙️ Setup Instructions
```bash
# 1️⃣ Clone the repository
git clone https://github.com/Payaljadhav30/Emotion-Based-Music-player.git

# 2️⃣ Move into the folder
cd Emotion-Based-Music-player

# 3️⃣ Create a virtual environment
python -m venv venv
venv\Scripts\activate

# 4️⃣ Install dependencies
pip install -r requirements.txt

# 5️⃣ Run the app
python app.py

