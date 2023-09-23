# PacMan_Java_Game
 PacMan Game Built using Java
 
## Description

The Pacman game is a classic arcade-style game implemented in Java using the Swing library. In this game, you control Pacman, a yellow character, and your goal is to eat all the dots while avoiding ghost enemies. The game features multiple levels, increasing difficulty, and a scoring system.

## How to Run the Game

1. **Prerequisites**:
   - Make sure you have Java installed on your computer.

2. **Clone the Repository**:
   - Clone or download the Pacman game repository to your local machine.

3. **Compile the Code**:
   - Open a terminal or command prompt and navigate to the directory containing the Pacman code files.

   - Compile the code using the following command:
     ```
     javac Pacman/Pacman.java
     ```

4. **Run the Game**:
   - Run the game using the following command:
     ```
     java Pacman.Pacman
     ```

5. **Game Controls**:
   - Use the arrow keys (Up, Down, Left, Right) to control Pacman's movement.
   - Press the **Space** key to start the game.
   - If you want to pause the game, press the **Escape** key.

6. **Objective**:
   - Eat all the dots in the maze while avoiding the ghosts.
   - Try to achieve the highest score possible.

7. **Game Over**:
   - The game ends when you lose all your lives (hearts).
   - You have three lives to start with.
   - You lose a life if a ghost catches Pacman.
   - The game continues until you decide to exit.

8. **Winning**:
   - To win a level, you must eat all the dots in the maze.
   - Each completed level increases the difficulty by adding more ghosts.

## Game Features

- Multiple levels with increasing difficulty.
- Scoring system to keep track of your progress.
- Lives (hearts) to give you a few chances.
- Ghost enemies that chase Pacman.
- Pause and resume functionality using the **Escape** key.

## Customization

You can customize the game by modifying the following aspects of the code:

- **Maze Layout**:
  - You can change the layout of the maze by modifying the `levelData` array in the `PacmanLogic` class. The numbers in this array represent different maze elements, such as walls, dots, and power-ups.

- **Game Speed**:
  - Adjust the game's speed by changing the `timer` object's delay in the `PacmanLogic` class constructor. The lower the delay value, the faster the game will run.

- **Graphics**:
  - Replace the image files in the `images` directory with your own graphics to customize Pacman, ghosts, and other visual elements.

## Known Issues

- There are no known issues with this code as of the last update in September 2021. However, you may encounter compatibility or performance issues on newer Java versions or platforms. Please check for updates or community support if needed.

## Credits

This Pacman game code is based on a classic arcade game and has been implemented for educational purposes. The code and graphics used in this project are inspired by the original Pac-Man game developed by Namco.

## License

This code is provided as-is and is for educational purposes only. You may use and modify the code for personal or educational purposes. Please review the licensing terms of any third-party libraries or assets used in this project.

Enjoy playing Pacman!

