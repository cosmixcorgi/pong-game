# Pong Game

A simple Pong game built with Python using the Turtle module. This game includes two paddles and a bouncing ball. Players can control the paddles to prevent the ball from going out of bounds, and each player scores when the opposing player fails to bounce the ball back.

## Game Features

- **Single or Two-Player**: Control both paddles with separate keys.
- **Scoreboard**: Displays scores for each player.
- **Ball Bouncing**: Ball bounces off the paddles and screen edges.
- **Speed Control**: The ball speed increases as the game progresses.

## How to Play

1. **Right Paddle Controls**:
   - Up Arrow (`↑`) - Move up
   - Down Arrow (`↓`) - Move down

2. **Left Paddle Controls**:
   - `W` - Move up
   - `S` - Move down

3. The goal is to keep the ball in play by preventing it from crossing the screen's edge behind the paddle.

4. The game ends when you close the window.

## Project Structure

- `main.py`: The main script to run the game, initializing the screen, paddles, ball, and scoreboard.
- `paddle.py`: Defines the paddle object and its movements.
- `ball.py`: Defines the ball object, including its movement, bouncing, and reset functionality.
- `scoreboard.py`: Handles scoring and displays it on the screen.

## Installation

1. Ensure you have Python installed on your computer.
2. Clone this repository.
3. Run the following command to start the game:

   ```bash
   python main.py
