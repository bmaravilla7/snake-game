# 🐍 Snake Game

A classic implementation of the Snake game built using Python and PyGame. This project showcases event-driven programming, real-time rendering, and collision detection in a grid-based system.

---

## 🚀 Features
- Smooth grid-based movement
- Dynamic food spawning
- Real-time score tracking
- Adjustable difficulty
- Clean game over screen
- Keyboard support (WASD / Arrow Keys)

---

## 📦 Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/bmaravilla7/snake-game.git
cd snake-game

# 2. (Optional) Create and activate a virtual environment
python3 -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# 3. Install dependencies
pip install pygame

# 4. Run the game
python snake.py
```

---

## 🎮 Controls
| Key        | Action     |
|------------|------------|
| W / Up     | Move Up    |
| S / Down   | Move Down  |
| A / Left   | Move Left  |
| D / Right  | Move Right |
| Esc        | Quit Game  |

---

## ⚙️ Configuration

Adjust the difficulty in `snake.py`:

```python
difficulty = 25  # Try 10 (Easy), 25 (Medium), 40+ (Hard)
```

---

## 📁 Project Structure

```
snake-game/
├── snake.py
├── README.md
└── .gitignore
```

---

## 📌 Future Improvements
- Sound effects
- Pause menu
- Score saving (high scores)
- Difficulty scaling
- Theming and visual skins
