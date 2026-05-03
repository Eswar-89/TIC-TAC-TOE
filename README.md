# 🎮 Tic Tac Toe Game

A simple and interactive **Tic Tac Toe** game built using **HTML, CSS, and JavaScript**. This project demonstrates core concepts like DOM manipulation, event handling, and game logic.

---

## 🚀 Live Demo

👉 https://eswar-89.github.io/TIC-TAC-TOE/

---

## 📌 Features

- 🎯 Two-player gameplay (X vs O)
- 🔄 Restart game functionality
- 🧠 Win detection logic
- 🤝 Draw detection
- ⚡ Real-time turn indicator
- 🖱️ Click-based interaction

---

## 🛠️ Tech Stack

- **HTML5** – Structure  
- **CSS3** – Styling & Grid Layout  
- **JavaScript (Vanilla)** – Game Logic  

---

## 📂 Project Structure

```
TIC-TAC-TOE/
│── index.html
│── style.css
│── index.js
```

---

## 📜 How It Works

- The board has **9 cells (3×3 grid)**.
- Players take turns placing **X** and **O**.
- The game checks for a winner after each move.
- If all cells are filled and no winner → **Draw**.
- Click **Restart** to play again.

---

## 🧠 Game Logic

Winning patterns used in the game:

```js
const winConditions = [
  [0, 1, 2],
  [3, 4, 5],
  [6, 7, 8],
  [0, 3, 6],
  [1, 4, 7],
  [2, 5, 8],
  [0, 4, 8],
  [2, 4, 6],
];
```

The game checks these combinations after every move to determine the winner.

---

## ▶️ How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/Eswar-89/TIC-TAC-TOE.git
```

2. Open the folder

3. Run the project:
- Open `index.html` in your browser

---

## 📄 License

This project is open-source and available under the **MIT License**.
