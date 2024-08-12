
# Egg Catcher Game

Egg Catcher is a simple and fun arcade-style game built using Python's Tkinter library. The objective of the game is to catch as many falling eggs as possible using a catcher before they hit the ground. The game speeds up as you progress, increasing the challenge.

## Features

- **Colorful Eggs:** Eggs are generated in different colors, adding visual variety to the game.
- **Score Tracking:** Your score increases as you successfully catch eggs.
- **Lives System:** You start with 3 lives, and you lose a life each time you miss an egg. The game ends when all lives are lost.
- **Increasing Difficulty:** The speed of the falling eggs increases gradually, making the game more challenging as you progress.

## How to Play

- Use the **Left Arrow** key to move the catcher to the left.
- Use the **Right Arrow** key to move the catcher to the right.
- Try to position the catcher under the falling eggs to catch them.
- If an egg reaches the bottom of the screen without being caught, you lose a life.
- The game continues until you run out of lives.

## Getting Started

### Prerequisites

- Python 3.x installed on your system.
- Tkinter library (usually comes pre-installed with Python).

### Installation

1. Clone this repository to your local machine:

   ```sh
   git clone https://github.com/aditikute24/Egg-Catcher-Python.git
   ```

2. Navigate to the project directory:

   ```sh
   cd Egg-Catcher-Python
   ```

3. Run the game:

   ```sh
   python egg_catcher.py
   ```

## Code Overview

The game is built using Python's `Tkinter` library and follows a simple structure:

- **Canvas Setup:** The game canvas is set up with a blue sky background and a green ground.
- **Egg Creation:** Eggs are created at random horizontal positions and fall down the screen.
- **Catcher Movement:** The catcher is controlled using the left and right arrow keys to catch the falling eggs.
- **Collision Detection:** The game checks if an egg has been caught by the catcher or missed.
- **Score and Lives:** The score is updated for each egg caught, and lives are reduced for each egg missed.
