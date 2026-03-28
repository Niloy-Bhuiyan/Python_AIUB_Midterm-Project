
---

# 🟡 Pac-Man Game (Python - AIUB Midterm Project)

A classic **Pac-Man-style arcade game** built using **Python and Pygame**, developed as part of an academic midterm project at AIUB.

This version includes **high score persistence using a JSON file**, so the player’s high score is saved even after closing the game.

---

## 🎮 Features

* 🟡 Smooth Pac-Man movement and controls
* 👾 Multiple ghosts with independent behavior
* 🔵 Power-up mode to eat ghosts
* ❤️ Lives system with game over handling
* 🎵 Sound effects and background music
* 🧠 Score and high score tracking (**saved in JSON**)
* 🎨 Simple and clean game graphics

---

## 🛠️ Technologies Used

* **Python 3**
* **Pygame Library**
* **JSON** (for high score persistence)

---

## 📸 Preview

*(Add a screenshot or GIF of your game here for a better GitHub presence)*

---

## 🚀 Getting Started

Follow these steps to run the project on your local machine.

---

### 🔹 1. Clone the Repository

```bash
git clone https://github.com/Niloy-Bhuiyan/Python_AIUB_Midterm-Project.git
```

---

### 🔹 2. Navigate to the Project Folder

```bash
cd Python_AIUB_Midterm-Project
```

---

### 🔹 3. Create a Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate it:

* **Windows:**

```bash
venv\Scripts\activate
```

* **Mac/Linux:**

```bash
source venv/bin/activate
```

---

### 🔹 4. Install Dependencies

```bash
pip install pygame
```

---

### 🔹 5. Run the Game

```bash
python pacman.py
```

---

## 🎮 Controls

* ⬆️ **Arrow Up** – Move Up
* ⬇️ **Arrow Down** – Move Down
* ⬅️ **Arrow Left** – Move Left
* ➡️ **Arrow Right** – Move Right
* 🔄 **R** – Restart after Game Over

---

## 💡 Game Objective

* Eat all the dots to increase your score
* Avoid ghosts unless you have a power-up
* Use power pellets to turn ghosts blue and eat them
* Survive as long as possible
* Beat and **save the high score**

---

## 📁 Project Structure

```
Python_AIUB_Midterm-Project/
│
├── pacman.py              # Main game file
├── board.py               # Maze layout and board logic
├── images/                # Game assets (sprites)
├── sounds/                # Sound effects and music
├── highscore.json         # JSON file to save high score
├── fonts/                 # Font files (if any)
└── README.md
```

---

## 🐛 Known Issues

* Ghost behavior may vary slightly depending on system performance
* Collision detection may need tuning in some edge cases

---

## 🙌 Acknowledgements

* Inspired by the classic **Pac-Man** arcade game
* Built as part of an academic project at **AIUB**

---

## 📜 License

This project is for educational purposes. Feel free to use and modify it.

---

## ⭐ If You Like This Project

Give the repository a ⭐ on GitHub to support the work!

---
