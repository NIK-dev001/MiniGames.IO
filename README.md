# 🎮 MiniGames.io

A lightweight, single-page application (SPA) platform for browser-based mini-games. Built with pure Vanilla JavaScript and Tailwind CSS — no frameworks, no build tools, no dependencies.

🔗 **[Play Now](https://nik-dev001.github.io/MiniGames.IO/)**

## ✨ Features

-   **3 Unique Games:** Tic-Tac-Toe (with Minimax AI), Chess, and Dice.
-   **Smart AI:** Tic-Tac-Toe bot uses the Minimax algorithm to play optimally or make human-like mistakes.
-   **Full Localization:** Supports English and Russian with a dynamic translation system.
-   **Theming Engine:** 4 built-in themes (Dark Classic, Galaxy Purple, Blue Classic, White Light) using CSS variables.
-   **Responsive Design:** Fully adaptive layout that works on desktop, tablet, and mobile devices.
-   **Zero Dependencies:** Runs entirely in the browser. No backend, no database, no external APIs.

## 🛠 Tech Stack

-   **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+)
-   **Styling:** Tailwind CSS (via CDN), Custom CSS Variables
-   **Architecture:** SPA routing, State management, Modular game logic
-   **Hosting:** GitHub Pages

## 🧠 Algorithms & Logic

### Tic-Tac-Toe AI
The bot implements the **Minimax algorithm** with adjustable difficulty:
-   **Optimal Play (56% chance):** Uses recursive tree search to find the best possible move.
-   **Human-like Play (44% chance):** Makes random valid moves to simulate realistic gameplay.

### Chess Engine
-   Piece movement validation for all 6 piece types.
-   Dynamic highlighting of valid moves and captures.
-   Basic bot logic that prioritizes capturing opponent pieces.

##  Local Development

1.  Clone the repository:
    ```bash
    git clone https://github.com/NIK-dev001/MiniGames.IO.git
    ```
2.  Open `index.html` directly in any modern browser.
3.  No server or installation required.

##  License

This project is licensed under the **GNU General Public License v3.0**. See the [LICENSE](LICENSE) file for details.

##  Author

**NIK-dev**
-   GitHub: [@NIK-dev001](https://github.com/NIK-dev001)
-   Email: nik.gg.00@inbox.ru
