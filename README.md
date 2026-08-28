# Canvas Snake Game

A lightweight, modular 2D Snake game built with vanilla JavaScript, HTML5 Canvas, and modern CSS. Designed with clean separation of concerns for easy extension and customization.

---

## 🚀 Overview

This repository contains an object-oriented, event-driven implementation of the classic Snake arcade game. The codebase is broken down into dedicated modules for rendering logic, input handling, and main game mechanics to maintain clean architecture.

## 📁 Repository Structure

* **`Index.html`** — Main entry point containing the game canvas container and UI frame.
* **`style.css`** — CSS rules governing layout, canvas alignment, color palette, and responsive design.
* **`Game.js`** — Main game controller managing the game loop, state management, and score tracking.
* **`Input.js`** — Handles keyboard event listeners, key bindings, and directional validation to prevent standard self-collision inputs.
* **`render.js`** — Dedicated drawing functions for rendering the grid, snake body segments, and food items to the canvas.
* **`README.md`** — Project documentation.

## 🛠️ Features

* **Modular Architecture:** Logic, input handling, and rendering are split into dedicated files for maintainability.
* **Zero Dependencies:** Built entirely with native Web APIs (HTML5 Canvas & Vanilla JS).
* **Responsive Canvas:** Adapts to modern browser displays for smooth frame updates.

## 🏁 Quick Start

### Prerequisites
* Any modern web browser (Chrome, Firefox, Edge, Safari).

### Local Setup
1. Clone the repository:
   ```bash
   git clone [https://github.com/Bytesblazer2/](https://github.com/Bytesblazer2/)<repository-name>.git
Navigate to the project directory:
cd <repository-name>
Open Index.html in your preferred browser.
🎮 How to Play
​Up / Down / Left / Right Arrows (or WASD): Change snake direction.
​Goal: Eat the spawned food items to grow the snake and increase your total score.
​Game Over: Hitting the canvas borders or running into your own tail ends the game.
