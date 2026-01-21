# 🌌 UniVerse

UniVerse is a desktop productivity application built with **Python and wxPython**.  
It combines three essential student tools into one simple interface.

---

## 🚀 Features

### 📝 To-Do List
- Add tasks
- Remove completed tasks
- Clear all tasks

### ⏱️ Pomodoro Timer
- 25-minute work sessions
- 5-minute break timer
- Start, Stop, and Reset buttons

### 🧠 Flashcards
- Add flashcards (front & back)
- View flashcards one at a time
- Reveal answers
- Delete all flashcards
- Flashcards are saved locally in a JSON file

---

## 📁 Project Structure

UniVerse/
├── UniVerse.py              # Main application launcher
├── app.py                   # Flashcards UI
├── flashcards_manager.py    # Flashcards logic & file handling
├── flashcards.json          # Flashcards storage
└── README.md                # Project documentation

---

## 🧰 Requirements

- Python 3.8 or higher
- wxPython library

---

## 📦 Installation

### Step 1: Install Python
Check if Python is installed:

python --version

If not installed, download it from:
https://www.python.org/downloads/

---

### Step 2: Install wxPython

Run this command in your terminal or command prompt:

pip install wxPython

(Note: Installation may take a few minutes.)

---

## ▶️ How to Run the Application

### Step 1: Open a terminal and navigate to the project folder

cd UniVerse

### Step 2: Run the main file

python UniVerse.py

The UniVerse homepage will open with three options:
- To-Do List
- Pomodoro Timer
- Flashcards

---

## 💾 Flashcards Storage

All flashcards are automatically saved in:

flashcards.json

Your data will remain saved even after closing the application.

---

## 🛠️ Future Improvements

- Save To-Do List data permanently
- Pomodoro sound notifications
- Flashcard categories
- Dark mode
- Progress tracking

---

## 👨‍💻 Author

Developed using **Python and wxPython** as a productivity and learning project.

🌟 UniVerse — one app, many study tools.
