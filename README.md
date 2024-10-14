## **Snake Game**

# Snake Game using Python and Turtle Graphics

This is a classic **Snake Game** built using Python's Turtle graphics module. The game includes features such as collision detection, a scoreboard that tracks the current score, and high score persistence saved to a text file.

## Features
- **Responsive Controls**: Control the snake using arrow keys (Up, Down, Left, Right).
- **Food Collision**: When the snake eats food, it grows and the score increases.
- **Wall and Tail Collision**: The game resets if the snake hits the wall or its own tail.
- **Scoreboard**: Displays the current score and the highest score achieved, which is stored in a `data.txt` file.
  
## Game Preview
- **Snake Movement**: The snake moves forward continuously. Use the arrow keys to change direction.
- **Eating Food**: When the snake touches the food, it grows, and the food reappears at a new random position.
- **Collision Detection**: The game resets when the snake hits the wall or itself, and the highest score is updated if a new record is achieved.

## Installation and Setup

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/snake-game-python.git
    cd snake-game-python
    ```

2. **Ensure Python is installed**:  
   This project uses Python 3.x. You can check if Python is installed by running:
    ```bash
    python --version
    ```

3. **Run the game**:  
   To start the game, run the following command:
    ```bash
    python main.py
    ```

## File Structure

- **`main.py`**: Contains the game loop, listens for user input, and handles the game's logic.
- **`snake.py`**: Defines the Snake class, handling movement, growth, and collision with walls and tail.
- **`food.py`**: Defines the Food class, handling food creation and random positioning.
- **`scoreboard.py`**: Defines the Scoreboard class, displaying the score and managing the high score using a `data.txt` file.
- **`data.txt`**: A text file that stores the highest score achieved.

## How to Play

- Use the arrow keys to control the direction of the snake.
- Eat the red food to grow the snake and increase your score.
- Avoid hitting the walls or the snake's tail; otherwise, the game will reset, and the score will restart.
- The highest score is saved automatically in the `data.txt` file.

## Requirements

- **Python 3.x**
- Turtle graphics module (comes pre-installed with Python)
