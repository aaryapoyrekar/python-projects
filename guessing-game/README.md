# 🎯 Guess the Number Game

A simple and fun terminal-based Python game where the user tries to guess a secret number between **1 and 99**.  
The game gives hints like 🔥 Hot, ❄️ Cold, or 🎉 Right to guide you!

---

## 📌 Game Rules

- A random number is generated between **1 (inclusive)** and **100 (exclusive)**.
- The user is prompted to guess the number.
- Based on the user's guess:
  - ❄️ **Cold**: If your guess is more than ±10 away from the secret number
  - 🔥 **Hot**: If your guess is within ±10 of the secret number
  - 🎉 **Right**: If your guess exactly matches the secret number

The game continues to prompt you until you guess it right!

---

## ▶️ How to Run

### ✅ Prerequisites

Make sure Python is installed. Check version using:

```bash
python --version
```

### 🏁 Run the Game

In your terminal or VS Code:

```bash
cd guessing-game
python guess_number.py
```

---

## 🛠️ Technologies Used

- Python 3
- `random` module
- Command Line Interface (CLI)

---

## 📁 Project Structure

```
guessing-game/
├── guess_number.py   # Main game file
└── README.md          # You're reading it!
```

---

## 💡 Future Enhancements (Try These Ideas!)

- 🎯 Add score tracking (number of attempts)
- ⏳ Limit the number of guesses (Game Over!)
- 💥 Add difficulty levels (easy, medium, hard)
- 🖼️ Build a GUI version with `Tkinter` or `PyGame`
- 🌐 Convert it into a web game using Flask or Django

---

## 🔗 Repository

This game is part of the [python-projects](https://github.com/YOUR_USERNAME/python-projects) repository, which contains beginner-friendly Python projects.

---

## 📜 License

This project is open-source and free to use under the [MIT License](https://choosealicense.com/licenses/mit/).

---

## 🙌 Acknowledgements

Made with ❤️ by Aarya Poyrekar  
Feel free to fork, play, and improve it! 🚀
