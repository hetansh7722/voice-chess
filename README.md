# 🎙️ Voice Chess

**Voice Chess** is a hands-free chess game you can play using your voice!  
Built with **Python**, **Flask**, **Speech Recognition**, and a browser-based chessboard.

---

## 🧩 What It Does

- 🎤 Control the game using voice commands like “move knight to F3”
- ♟️ Play on a web-based chessboard
- 🧠 Real-time speech-to-move conversion
- 💻 Flask backend handles logic and routing

---

## 🚀 How to Run (Localhost)

### 1. Clone the Repository

```bash
git clone https://github.com/vANSHBHATT2527/Voice_Chess.git
cd Voice_Chess
```

### 2. Create a Virtual Environment (Recommended)

**Windows:**

```bash
python -m venv venv
venv\Scriptsctivate
```

**macOS/Linux:**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

If the file is missing or doesn't cover all, install manually:

```bash
pip install flask speechrecognition pyaudio python-chess
```

⚠️ *Note:* PyAudio can be tricky to install.  
If needed, get a wheel from:  
[https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio](https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyaudio)

---

### 4. Start the App

```bash
python chess_game.py
```

You’ll see:

```
Running on http://127.0.0.1:5000/
```

---

### 5. Open the Web App

Go to your browser and visit:

```
http://localhost:5000
```

Make sure your browser **has microphone access enabled**.

---

## 🗂️ Project Structure

```
Voice_Chess/
│
├── static/           → JS, CSS, chessboard assets
├── templates/        → HTML files
├── chess_game.py     → Flask backend + voice control
├── requirements.txt  → List of Python dependencies
└── README.md         → You're reading it!
```

---

## ✅ Requirements

- Python 3.7+
- Flask
- SpeechRecognition
- PyAudio
- python-chess

---

## 🤝 Contribute

Found a bug or want to add a feature?  
Feel free to open an issue or submit a pull request!

---

## 📄 License

This project is licensed under the **MIT License**.
