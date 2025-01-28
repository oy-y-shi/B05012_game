# B05012_game
Retro Snake Revival
Overview
"Retro Snake Revival" is a modern remake of the classic Snake game using the Pygame library in Python. The goal of the game is simple: control the snake, eat food, and grow longer while avoiding collisions with the walls or the snake's own body.

This project aims to provide a nostalgic experience of the retro Snake game, while introducing modern features such as real-time game-over prompts and scoring.

Features
1.Snake Movement: Use the arrow keys to control the snake's direction (Left, Right, Up, Down).
2.Food: Eat the food that appears randomly on the screen to grow longer and increase your score.
3.Game Over Conditions: The game ends if the snake collides with the wall or itself.
4.Score Display: The score (based on the snake's length) is displayed on the top left corner.
5.Restart Option: After losing, you can restart the game or quit.
6.Retro Visuals: The game uses simple, colorful 2D graphics that mimic the classic Snake game style.

Game Controls
Arrow keys (Left, Right, Up, Down): Control the direction of the snake.
Q: Quit the game.
C: Restart the game after a loss.

How to Play
Start the Game: Run the script snake_game.py (or whatever the file is named).
Move the Snake: Use the arrow keys to guide the snake toward the food.
Eat the Food: Each time the snake eats the food, it will grow in length, and the score will increase.
Avoid Collisions: The game ends if the snake hits the wall or itself.
Game Over: When you lose, you can choose to restart the game by pressing C or quit by pressing Q.
Game Mechanics
Snake: The snake is initially one block long and starts at the center of the screen. As it eats food, its length increases by one block.
Food: Randomly placed on the screen. Each time the snake eats it, the snake's length increases by 1, and the food spawns at a new random position.
Game Over: The game ends when the snake collides with the boundaries of the screen or with itself.
Speed: The speed of the snake is constant and can be adjusted by modifying the SNAKE_SPEED variable in the code.

Code Breakdown
Key Functions
your_score(score): Displays the current score at the top-left corner of the screen.
draw_snake(block, snake_list): Draws each segment of the snake on the screen.
message(msg, color): Displays a message in the center of the screen with a specified color.
game_loop(): The main game loop that handles input, updates the game state, checks for collisions, and updates the screen.

Main Game Loop
The main loop runs continuously, updating the snake’s position and checking for user input.
When the snake eats food, a new piece of food is randomly generated, and the snake grows in length.
The game checks for collisions with the walls or the snake’s own body, and if any occur, the game ends.
The player is given the option to restart or quit after losing.
Screenshots
(Include any relevant screenshots here if you'd like to showcase the game in action.)

Enjoy the game and try to beat your high score!
