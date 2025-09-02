# 🐍 Snake Game (Python)

A classic **Snake Game** built using **Python** and the **Tkinter** GUI library.
The player controls the snake using arrow keys and tries to eat food to grow in size while avoiding collisions with walls and itself.

---

## 📸 Screenshot
* `![Snake Game](screenshot.png)`)*

---

## 🎮 Features
- Snake movement controlled by **Arrow Keys** (⬅️ ➡️ ⬆️ ⬇️)
- Food spawns at **random positions** on the canvas
- Score counter updates in real-time
- **Game Over** screen when snake collides with walls or itself
- Smooth gameplay with adjustable **speed**

---

## 🛠️ Technologies Used
- **Python 3.x**
- **Tkinter** (for GUI)
- **Random** module (for food placement)

---
## 🚀 How to Run the Game

1.  **Prerequisites**
    Make sure you have **Python 3.x** installed on your system. You can check by running:
    ```bash
    python --version
    ```

2.  **Clone the Repository**
    Clone this repository to your local machine.
    ```bash
    git clone [https://github.com/yourusername/snake-game.git](https://github.com/yourusername/snake-game.git)
    ```

3.  **Navigate to the Directory**
    Go into the project folder.
    ```bash
    cd snake-game
    ```

4.  **Run the Game**
    Execute the Python script.
    ```bash
    python snake_game.py
    ```

---

## 🎯 Controls

| Key       | Action     |
| :-------- | :--------- |
| `⬅️` Left  | Move Left  |
| `➡️` Right | Move Right |
| `⬆️` Up    | Move Up    |
| `⬇️` Down  | Move Down  |

---

## ⚙️ Game Settings

You can tweak these constant values at the top of the `snake_game.py` file to adjust gameplay:

```python
GAME_WIDTH = 1000        # Width of game window
GAME_HEIGHT = 700        # Height of game window
SPEED = 100              # Snake movement speed (lower = faster)
SPACE_SIZE = 25          # Size of each grid square
BODY_PARTS = 2           # Initial snake length
SNAKE_COLOR = "#00FF00"   # Snake color
FOOD_COLOR = "#FF0000"    # Food color
BACKGROUND_COLOR = "#000000" # Background color
```

## 📌 Future Improvements
[ ] Add difficulty levels (e.g., Easy, Medium, Hard)

[ ] Add a "Restart" button after Game Over

[ ] Add sound effects for eating food and game over

[ ] Implement high score tracking that persists between sessions


## 🏆 Credits
Developed by [Aarya Poyrekar] ✨

Inspired by the classic Snake Game.
