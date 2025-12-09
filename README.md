# Week 6 Lab: Canvas Animation Game 🎮✨

## 📖 Scenario/Summary
As discussed and demonstrated in our lesson this week, animating the contents of the **canvas element** is our goal.  
This lab creates a simple game using animated balls and mouse clicks to pop them.  

You will write JavaScript code to:
- Create and animate a group of balls with:
  - Different starting positions  
  - Different x and y velocities  
  - Different radii  
  - Different colors  
- Control collisions of balls with the canvas walls (ignoring ball-to-ball collisions).  
- Add interactivity with mouse clicks to burst balls.  
- Display a **Game Over** message when all balls are popped.  
- Provide a button to restart the game.  

---

## 🖼️ Features

- **Dual Canvas Setup**:  
  - Background canvas  
  - Foreground canvas for balls and action  

- **Ball Class**:  
  - Encapsulates properties (position, velocity, radius, color)  
  - Methods for drawing, updating, and bursting  

- **Game Functions**:  
  - `startGame()` → Instantiates N balls and stores them in an array  
  - `gameLoop()` → Updates and redraws balls continuously  
  - Random property generators for ball attributes  

- **Interactivity**:  
  - Event listener for mouse clicks  
  - Function to detect mouse position and check if inside a ball  
  - Burst function removes ball and plays sound  

- **Game Over**:  
  - Ends game when all balls are popped  
  - Displays score and message  

- **Restart Button**:  
  - Resets game state and starts again  

---

## 📂 Project Structure

Week6Lab/ │ ├── index.html # Main HTML file ├── sounds/ # Folder containing pop.wav sound └── README.md # Documentation


---

## ⚙️ Requirements

- **Text Editor**: Brackets, Notepad++, VS Code, or any code-aware editor  
- **Browser**: Chrome, Firefox, Safari, or Edge  
- **Server**: Career Web Portfolio (CWP) server for uploading labs  

---

## 🚀 How to Run

https://dgilpin3.github.io/Bubble-Pop/

📝 Notes
The lab demonstrates object-oriented programming (OOP) in JavaScript with classes.

Animations use requestAnimationFrame() for smooth rendering.

Mouse events provide interactivity and game logic.

Creativity is encouraged—experiment with ball colors, velocities, sounds, and additional effects.
