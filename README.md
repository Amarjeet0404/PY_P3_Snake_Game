# 🐍 Snake Game using Python Turtle

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Game](https://img.shields.io/badge/Game-Snake-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 🎮 Project Overview

This project is a **classic Snake Game** developed using **Python and Turtle Graphics**. The objective of the game is to control a snake, guide it to eat food, and grow longer while avoiding collisions with the walls or the snake’s own body.

The project demonstrates **basic game development concepts** such as object movement, collision detection, event handling, and score tracking using Python.

---

## 📌 Features

* 🐍 Smooth snake movement in four directions (Up, Down, Left, Right)
* 🍎 Random spawning of food items
* 📊 Score tracking system
* 🚧 Boundary collision detection
* 💥 Self-collision detection
* 🔁 Restart the game using **'R' key**
* 🎮 Simple and interactive gameplay

---

## 🛠 Technologies Used

| Technology      | Purpose                     |
| --------------- | --------------------------- |
| Python          | Programming language        |
| Turtle Graphics | Game graphics and animation |
| Random Module   | Random food spawning        |

---

## 🎯 How to Play

1. Run the Python script to start the game.
2. Control the snake using the **Arrow Keys**:

| Key           | Action     |
| ------------- | ---------- |
| ⬆ Up Arrow    | Move Up    |
| ⬇ Down Arrow  | Move Down  |
| ⬅ Left Arrow  | Move Left  |
| ➡ Right Arrow | Move Right |

3. Eat the **food items** to grow longer and increase your score.
4. Avoid hitting:

   * The **walls**
   * The **snake’s own body**
5. If the snake crashes, the **game ends**.
6. Press **'R'** to restart the game.

---

## ⚙️ Code Structure

The code is organized into the following main components:

### 1️⃣ Initialization

* Creates the game window
* Initializes the snake and food objects
* Sets initial score and game state

### 2️⃣ Direction Control

Functions that handle keyboard input:

* Move Up
* Move Down
* Move Left
* Move Right

### 3️⃣ Snake Movement

* Updates snake position
* Handles snake growth after eating food
* Checks collision with boundaries and body

### 4️⃣ Score Management

* Updates score when food is eaten
* Displays score on screen

### 5️⃣ Game Over & Restart

* Detects collision with wall or snake body
* Displays **Game Over**
* Allows restart using **'R' key**

### 6️⃣ Border Drawing

* Creates a visible boundary for the game area

---

## 📂 Project Structure

```
Snake-Game
│
├── snake_game.py
├── README.md
└── assets (optional)
```

---

## 🚀 Future Improvements

Possible enhancements for this project:

* 🔊 Add **sound effects and background music**
* ⚡ Introduce **difficulty levels**
* 🎨 Add **custom snake colors and themes**
* 🏆 Implement **high score leaderboard**
* 🌐 Create an **online multiplayer version**

---

## 👨‍💻 Author

**Amarjeet Singh Chauhan**

🔗 GitHub:
https://github.com/Amarjeet0404

---

⭐ If you like this project, consider **starring the repository!**

Happy Coding & Happy Gaming! 🐍🎮
