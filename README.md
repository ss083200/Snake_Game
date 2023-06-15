# Snake_Game
 Snake Game implemented in Python using Turtle graphics. Control the snake, eat food, and avoid collisions to achieve a high score.

This repository contains a classic Snake Game implemented in Python. The game consists of several files that work together to create an interactive gaming experience.

The main file, main.py, launches the Snake Game using the Turtle graphics module. The game window is set up with a black background and a title. The snake, food, and score are initialized, and the necessary event listeners for keyboard inputs are set up. The game loop runs continuously, updating the screen, moving the snake, and detecting collisions with food, walls, and the snake's own tail. The game ends when a collision occurs, and the final score is displayed.

The snake.py file defines the Snake class, responsible for managing the snake's segments, movement, and direction. The snake grows in length when it consumes food and moves through the game grid based on user inputs.

The food.py file contains the Food class, which represents the food item for the snake to eat. The food appears as a cyan-colored circle at random positions on the screen, refreshing its location whenever the snake consumes it.

The scorecard.py file defines the Scoreboard class, responsible for displaying and updating the player's score. The score increases each time the snake eats food, and when the game ends, the final score and a "GAME OVER" message are displayed.

The game is built by implementing OOPS and tried to keep the code mosular.
