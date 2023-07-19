# Snake Game
This is a simple Snake game developed in Python using the Turtle graphics library. The game allows the player to control a snake, represented as a chain of squares, and the objective is to eat the yellow food that appears randomly on the screen, increasing the snake's length. The game ends if the snake collides with the wall or itself.

## How to Play
<b>Install Python:</b> Make sure you have Python installed on your computer. If not, download and install the latest version from the official Python website (https://www.python.org/downloads/).

<b>Clone the Repository:</b> Clone or download the repository to your local machine.

<b>Run the Game:</b> Navigate to the directory where the files are located and run the "main.py" file using Python. This will start the game, and a window will appear showing the Snake game board.

<b>Controls:</b> Use the following controls to move the snake:
<ul>
    <li>Up: Press the "w" key.</li>
    <li>Down: Press the "s" key.</li>
    <li>Right: Press the "d" key.</li>
    <li>Left: Press the "a" key.</li>
</ul>

<b>Game Rules:</b> The snake moves continuously in the direction it's facing. The objective is to eat the yellow food to increase the snake's length. The game ends if the snake collides with the wall or itself.

<b>Highest Score:</b> The game keeps track of your highest score in the "data.txt" file. It updates the highest score whenever you beat your previous record.

<b>Restart:</b> If the snake collides with the wall or itself, the game will restart automatically. Your score will be reset, but your highest score will remain unchanged.

## Files Overview
<b>main.py:</b> This file contains the game's main loop and sets up the game window using the Turtle library. It creates instances of the Snake, Food, and ScoreBoard classes and handles user input for controlling the snake.

<b>snake.py:</b> This file defines the Snake class, which manages the snake's behavior. It creates the snake's segments, allows the snake to move, extend its length, and detect collisions with walls and itself.

<b>food.py:</b> This file defines the Food class, which represents the yellow food that appears randomly on the screen. It handles the food's appearance and refreshes its position whenever the snake eats it.

<b>scoreboard.py:</b> This file defines the ScoreBoard class, responsible for keeping track of the player's score and highest score achieved in the game. It displays this information on the game screen.

<b>data.txt:</b> This file stores the highest score achieved in the game. The game reads and updates this file to keep track of the highest score.

## Acknowledgments
The Snake game was developed using the Python Turtle graphics library and is inspired by the classic Snake game. It was created as a fun programming exercise and learning experience.

Have fun playing the Snake game! If you have any suggestions or feedback, feel free to contribute or reach out to the developer. Enjoy!