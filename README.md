# 🧠 Flashcards – Learn French Vocabulary

**Flashcards** is an interactive Python application designed to help you memorize French vocabulary efficiently.  
It uses a simple flashcard mechanism: first shows you the French word, then flips the card after 3 seconds to reveal the English translation.  
If you know the word, simply click the ✅ button — the word will be removed from your learning list!

---

## ✨ Features

- 🕒 Timed card flip from French to English (3 seconds)
- ✅ Mark known words to remove them from future sessions
- 📄 Automatically saves progress in `words_to_learn.csv`
- 🖼️ Simple, clean and responsive GUI with `Tkinter`
- 📊 Uses `pandas` for data handling

---

## 🚀 Getting Started

### 1. Clone the Repository
### 2. Install Dependencies
  - Only one external dependency is needed:
  - pip install pandas
### 3. Run the app: main.py

---

## 🗂️ Project Structure

flashcards/
├── data/
│   ├── french_words.csv          # The main word list
│   └── words_to_learn.csv        # Generated automatically
├── images/
│   ├── card_front.png
│   ├── card_back.png
│   ├── right.png
│   └── wrong.png
├── main.py

---

## 🧠 How It Works
- A random French word is displayed.
- After 3 seconds, the card flips to show its English meaning.
- If you know the word, click ✅ to remove it from your word list.
- Otherwise, click ❌ to skip and move to the next word.
- Your learning progress is saved automatically.

---

## 🛠️ Requirements
- Python 3.x
- pandas
- tkinter (usually pre-installed with Python)

---

## 🎯 Future Improvements (Ideas)
- Add support for custom word lists
- Support multiple languages
- Track learning statistics
- Add dark mode UI
- Spaced repetition algorithm

---

## 📃 License
- This project is licensed under the MIT License.
- Feel free to use, modify, and share it.

## Contact
- tolgayilmaz1377@gmail.com
