# Lights-Out-Puzzle-Solver-Online
An interactive, responsive solver and trainer for the classic Lights Out puzzle game on grids up to 15x15. Built with pure HTML, CSS, and JavaScript.
# Lights Out — Solver & Trainer

A sleek, responsive interactive solver and training simulator for the classic **Lights Out** puzzle game. Built purely with semantic HTML5, modern CSS grid/variables, and vanilla JavaScript.

## 🚀 Live Demo
👉 **[CLICK HERE TO PLAY THE LIVE DEMO](YOUR_GITHUB_PAGES_LINK_HERE)** 

## 🧠 How It Works
The app uses **Gaussian Elimination over the Galois Field $GF(2)$** to solve the puzzle matrix. 
* Pressing a cell toggles its state along with its orthogonal neighbors (Up, Down, Left, Right).
* The linear algebra solver determines the precise click configuration required to transition the board to an all-off state.
* If multiple solution sets exist, the engine resolves a valid matrix layout and transitions you smoothly into a guided **Practice Mode**.

## ✨ Features
* **Custom Dimensions:** Works with standard configurations ($5 \times 5$) up to massive grids ($15 \times 15$).
* **Rectangular Support:** Fully supports non-square layouts (e.g., $5 \times 6$).
* **Dual-Mode Architecture:** 
  * **Edit Mode:** Draw or replicate any real-world board state.
  * **Play/Practice Mode:** Walk step-by-step through the solution sequence with an interactive, pulsing visual guide.
* **Pure Performance:** Zero external dependencies, no framework bloat, and fully responsive CSS layouts.

## 🛠️ Installation & Local Setup
No compilation or server configuration is required.
1. Clone or download this repository.
2. Open `index.html` directly in any modern web browser.
