# Breakout
A simple Breakout game created using Python's Turtle module. The game involves a paddle, a bouncing ball, and bricks. Your goal is to break all the bricks by bouncing the ball using the paddle.

## Features
- Classic Breakout-style gameplay.
- Paddle to control the ball's direction.
- Bricks of various colors arranged in rows.
- Tracks player's score and remaining lives.
- Win or lose conditions.

## Gameplay Instructions
1. Start the game:
    Run the Python script to start the game.
2. Controls:
    - Press the Left Arrow key to move the paddle left.
    - Press the Right Arrow key to move the paddle right.
3. Objective:
    Use the paddle to bounce the ball and break all the bricks.
4. Game Over:
    - You lose a life if the ball falls below the paddle.
    - The game ends if you run out of lives.
5. Winning:
    Clear all the bricks to win the game.

## Setup and Installation
1. Make sure Python 3.10 or above is installed on your system.
2. Install any required libraries if not already installed (e.g., turtle is pre-installed in Python).
3. Clone this repository or download the script.
4. Run the script using:
   ```
   python breakout_game.py
   ```
## Code Structure
The project is organized into several classes:
1. Paddle:
   Represents the player's paddle. Handles movement and boundaries.
2. Ball:
   Represents the bouncing ball. Handles movement, collisions, and resets.
3. BrickManager
   Manages the creation and handling of bricks
4. BreakoutGame
   The main game class integrates all components and handles game logic, collisions, scoring, and rendering.

## Customization
You can modify the following parameters to customize the game:
- Screen Dimensions: SCREEN_WIDTH, SCREEN_HEIGHT
- Paddle Speed: PADDLE_SPEED
- Ball Speed: BALL_SPEED
- Brick Colors and Layout: Edit the create_bricks method in the BrickManager class.

## Future Improvements
- Add levels with increasing difficulty.
- Include sound effects for collisions.
- Implement a high-score tracking system.
- Implement a pause/resume feature.

## Screenshots
![image](https://github.com/user-attachments/assets/d12c1625-062a-47e7-8a04-84fa677647a7)

