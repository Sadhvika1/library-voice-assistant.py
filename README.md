
# 📚 Library Voice Assistant

A **Python-based voice assistant** that helps users locate books in a library using **speech recognition** and **text-to-speech**.  
Instead of searching manually, users can simply **speak a rack number**, and the assistant will respond with the subject and books available in that rack.

---

## ✨ Features
- 🎤 **Voice Recognition**: Speak commands like *“rack number 1”* to search.
- 🔊 **Text-to-Speech (TTS)**: The assistant speaks back results using `pyttsx3`.
- 📖 **Predefined Book Database**: Maps racks to subjects and book titles.
- ♻️ **Continuous Interaction**: Keeps listening until you say *“stop”*.
- 🖥️ **Console Output**: Displays rack details in a neat table.

---

## 🛠️ Tech Stack
- **Programming Language**: Python 3  
- **Libraries**:
  - [`speech_recognition`](https://pypi.org/project/SpeechRecognition/) → for capturing user voice  
  - [`pyttsx3`](https://pypi.org/project/pyttsx3/) → for text-to-speech  
  - `sys`, `os` → system operations  
  - *(Imports like `wikipedia`, `pywhatkit`, `requests` are available but not used in the current version)*

## 📂 Project Structure
    📦 library-voice-assistant
┣ 📜 Speech.py # Main program file
┣ 📜 list_of_books.txt # Sample book list file
┗ 📜 README.md # Project documentation

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/Sadhvika1/library-voice-assistant.py
cd library-voice-assistant.py

pip install speechrecognition pyttsx3
TO run 
python Speech.py


