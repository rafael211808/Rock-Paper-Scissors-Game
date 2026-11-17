# ✊✋✌️ Rock Paper Scissors Game

An interactive, modern game of **Rock, Paper, Scissors** developed using **HTML5**, **CSS3**, and **vanilla JavaScript**, featuring visual animations with emojis, a persistent scoring system, and advanced capabilities such as an automatic mode and keyboard shortcuts.

Webpage link: https://rafael211808.github.io/rock-paper-scissors-game/

---

## 🚀 Features

* **Interactive Gameplay:** Choose between Rock, Paper, or Scissors by clicking on buttons featuring corresponding icons.
* **Persistent Score (`localStorage`):** The game automatically tracks and saves your wins, losses, and ties in your browser, preserving your history even after refreshing the page.
* **Auto Play Mode:** An automated gameplay feature where the computer plays against itself at set intervals.
* **Keyboard Shortcuts:**
* `r` key: Selects Rock. 
* `p` key: Selects Paper. 
* `s` key: Selects Scissors. 
* `a` key: Toggles Auto Play mode on/off. 
* `Backspace` key: Resets the score (with an on-screen confirmation prompt).
* **Reset Confirmation:** A safety feature with confirmation buttons (Yes/No) to prevent the score from being cleared accidentally.

---

## 🛠️ Technologies Used

* **HTML5:** Interface structure, game action buttons, and result display elements.
* **CSS3:** Visual styling with a dark theme, Flexbox-based alignment, and custom designs for buttons and icons.
* **JavaScript:** Logic for the computer’s random selection, DOM manipulation, click/keyboard event handling, interval management, and local storage (`localStorage`).

---

## 📂 File Structure

```text
Rock-Paper-Scissors/
│
├── index.html    # Main game webpage
│
├── styles/
│   └── rock-paper-scissors.css # Styling and visual layout
│
├── scripts/
│   └── rock-paper-scissors.js  # Scoring logic, events, and game rules
│
└── images/
    ├── rock-emoji.png          # Rock icon
    ├── paper-emoji.png         # Paper icon
    └── scissors-emoji.png      # Scissors icon
