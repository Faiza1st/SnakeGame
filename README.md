# SnakeGame
This is a simple implementation of the classic Snake Game using Python and the pygame library. The player controls a snake that moves around the screen, collecting food while avoiding collisions with the walls or its own tail. The game increases in difficulty as the snake grows longer with each food item consumed.

## Features
Snake Movement: Control the snake using arrow keys (up, down, left, right).
Food Collection: The snake grows longer each time it eats food, which randomly appears on the screen.
Game Over: The game ends when the snake collides with itself or the wall.
Score Display: Your current score is shown in the top-left corner of the screen.
Increasing Difficulty: The snake's speed increases as its length grows, making the game progressively harder.

## Game 
<img width="590" alt="Screen Shot 2024-11-22 at 12 59 52 pm" src="https://github.com/user-attachments/assets/39c3cb0c-f5eb-4ed7-becb-c218ec3fbd56">


## Code Overview
The game is implemented using the pygame library, which handles the graphical rendering and input events. The core logic of the game is structured around the following components:
Game Loop: Continuously updates the snake's movement and checks for collisions.
Snake Class: Defines the snake's body, movement, and growth.
Food Class: Randomly generates food and checks if it has been eaten.
Collision Detection: Checks for collisions with walls or the snake’s own body.
Score Display: Shows the current score and updates as the snake eats food.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

