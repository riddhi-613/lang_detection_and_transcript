# 🎙️ Speech Language Detector & Translator

This Python project captures speech input using a microphone, detects the spoken language (English, Hindi, or Hinglish), and translates non-English speech into English using the `googletrans` library.

---

## 🚀 Features

- 🎧 Real-time speech recognition via microphone
- 🌐 Automatic language detection (English, Hindi, Hinglish)
- 🔁 Translation to English for Hindi or Hinglish inputs
- 🧠 Hinglish detection using custom trigger words
- 🔄 Continuous loop until manually stopped
- 🛑 Graceful exit using `Ctrl + C`

---

## 🧪 How It Works

1. The microphone captures your voice input.
2. The program first attempts to recognize speech in English.
3. If English recognition fails, it falls back to Hindi.
4. The detected text is then analyzed to determine its language:
   - If it's Hindi but contains English-like words (e.g., "is", "are", "hai", etc.), it's marked as **Hinglish**.
   - Otherwise, it's marked as **Hindi** or **English**.
5. If Hindi or Hinglish is detected, the sentence is translated into English.
6. Output is printed for both the original and translated versions (if applicable).

---

## 🖥️ How to Use

1. Clone this repository or copy the Python file.
2. Run the script using Python.
3. Speak clearly into the microphone when prompted with:

   <img width="704" height="41" alt="image" src="https://github.com/user-attachments/assets/a6d89352-df3f-40bf-926f-a79b7aab6681" />
5. View the output language detection and translation in the console.
6. Press Ctrl + C to exit the program at any time.

---
## 📋  Sample Output 
<img width="360" height="182" alt="image" src="https://github.com/user-attachments/assets/f5c1e35d-e3af-4c03-8691-c03a6c7a18f3" />
