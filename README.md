# Snake Game

A classic Snake game implemented in a single HTML file using HTML5 Canvas, Tailwind CSS, and JavaScript.

## Features

- **Responsive Design**: Works on both desktop and mobile devices.
- **Multiple Control Options**:
  - Keyboard: Arrow keys or WASD
  - Mobile: Swipe gestures or on-screen directional buttons
- **Game Mechanics**:
  - Adjustable speed settings (Slow, Normal, Fast, Insane)
  - Toggleable walls (on/off)
  - Score tracking with local storage for best score
- **Visual Elements**:
  - Gradient-colored snake with distinct head and body
  - Animated food item
  - Dark mode aesthetic with grid background
- **User Interface**:
  - Start/pause overlay with instructions
  - Game over screen with restart option
  - Score and best score display

## How to Play

1. Open `index.html` in a web browser.
2. Click the "Start Game" button or press Space/Tap to begin.
3. Control the snake using:
   - **Desktop**: Arrow keys or WASD
   - **Mobile**: Swipe in the desired direction or use the on-screen buttons
4. Guide the snake to eat the food (orange square) to grow and earn points.
5. Avoid hitting the walls (if enabled) or the snake's own body.
6. Pause/resume the game by pressing Space or tapping the game area.

## Settings

- **Speed**: Adjust the game speed using the dropdown menu (affects snake movement).
- **Walls**: Toggle wall collisions on or off using the "Walls: On/Off" button.

## Storage

- Your best score is saved in the browser's local storage and persists between sessions.

## Implementation Details

The game is contained entirely within a single HTML file:
- **HTML**: Structure and layout
- **Tailwind CSS**: Styling (loaded via CDN)
- **JavaScript**: Game logic, rendering, and interactions

The snake and food are drawn on an HTML5 canvas with smooth animations and visual feedback.
