# 🐍 Snake Game

**A classic snake game reimagined with modern web technologies**

![Snake Game Demo](demo.gif)
<!-- Replace with actual screenshot or animated GIF -->

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## About the Project

This is a portfolio showcase of a classic Snake game built entirely with vanilla JavaScript and HTML5 Canvas. The project demonstrates clean code organization, game development fundamentals, and a minimalist approach to web-based gaming—all contained in a single, self-contained HTML file with zero dependencies and no build process required.

Perfect for demonstrating foundational web development skills and game programming concepts in their purest form.

## Features

- **Smooth Canvas Rendering** - Fluid 400x400px game board with crisp graphics
- **Intuitive Controls** - Responsive arrow key input for seamless gameplay
- **Real-time Score Tracking** - Live score display as you collect food
- **Collision Detection System** - Wall and self-collision mechanics
- **Responsive Game Board** - Clean, centered layout that works across browsers
- **Single-file Architecture** - No bundlers, no frameworks, no dependencies

## Demo / How to Play

### Quick Start
Simply open `snake.html` in any modern web browser—no installation or setup required.

### Controls
- **↑ Arrow Key** - Move Up
- **↓ Arrow Key** - Move Down
- **← Arrow Key** - Move Left
- **→ Arrow Key** - Move Right

### Game Objective
Guide the snake to eat the red food squares. Each food item increases your score and grows the snake by one segment. Avoid hitting the walls or colliding with your own body!

### Scoring
- **+10 points** for each food item collected
- Game ends on collision—try to beat your high score!

## Technical Implementation

### Technologies Used
- **HTML5 Canvas API** - For rendering the game board and graphics
- **CSS3** - For styling and layout
- **Vanilla JavaScript (ES6)** - For game logic and interactivity

### Architecture Overview

The game is built using fundamental game development patterns:

- **Game Loop Pattern** - 100ms tick rate for consistent gameplay speed
- **Canvas-based Rendering** - Efficient 2D graphics rendering system
- **Event-driven Input** - Keyboard event listeners for responsive controls
- **Collision Detection** - Boundary checking and self-collision algorithms
- **State Management** - Snake position tracking, food generation, and score updates

### Key Technical Highlights
- **Single-file Design** - Entire game in ~215 lines of code
- **No Frameworks** - Pure JavaScript implementation
- **No Dependencies** - Works completely standalone
- **20x20 Grid System** - Each cell is 20px for clean movement

## Getting Started

### Prerequisites
- Any modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software or libraries needed

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd snake
   ```

2. **Open the game**
   ```bash
   open snake.html
   ```
   Or simply double-click `snake.html` in your file explorer.

### Browser Compatibility
Works on all modern browsers with HTML5 Canvas support (2015+).

## Project Highlights

This project demonstrates:

- **Clean Code Organization** - Well-structured JavaScript with clear separation of concerns
- **Vanilla JavaScript Mastery** - No frameworks needed for interactive experiences
- **Game Development Fundamentals** - Core concepts like game loops, collision detection, and state management
- **Canvas API Proficiency** - Efficient 2D rendering and animation techniques
- **Minimalist Design Philosophy** - Maximum functionality with minimal complexity

---

**Built with ❤️ as a portfolio demonstration of core web development skills**
