
# Brick Breaker Game in Python

## Installation
1. Install Python and add it to your system's environment variables.
2. Use pip to install the required modules:
   ```bash
   pip install pygame
   ```

## Game Rules
- The game consists of a paddle, a ball, and multiple layers of bricks.
- The player controls the paddle using the left (`←`) and right (`→`) arrow keys.
- The ball bounces off the walls and the paddle, breaking bricks upon contact.
- If the ball falls below the paddle, the player loses a life. The game ends when all lives are lost or all bricks are destroyed.

## Game Structure
The game is structured around three main classes:
- **Paddle**: Controls the player's paddle movement.
- **Ball**: Manages the ball's movement and collision detection.
- **Brick**: Represents the bricks that need to be destroyed.

## Game Loop
The main game loop handles the following:
- Checking for collisions between the ball, paddle, and bricks.
- Updating the game state and rendering graphics.
- Transitioning between levels upon clearing all bricks or ending the game.

## Running the Game
To start the game, run the following command in the command prompt:
```bash
python Game18.py
```

## Additional Resources
For the complete source code and further details, please refer to the related files.

## Acknowledgments
- Audio and image assets sourced from the internet. Apologies for any copyright issues.

## Contact
For more information, follow the WeChat account "Charles的皮卡丘" and reply with 'game18' to access related files.

