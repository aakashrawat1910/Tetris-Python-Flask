# Tetris-in-Python-with-Flask-API

## Description

This is a classic Tetris game built using Flask for the backend and HTML/CSS/JavaScript for the frontend. The game allows players to control falling Tetris blocks using keyboard or on-screen buttons. It includes functionalities such as starting a new game, pausing and resuming the game, rotating, and moving the blocks.

The game grid is designed to be visually clear, and the blocks fall at a constant speed, with players aiming to clear full lines to score points. It also includes a "Pause/Resume" feature to temporarily halt the game.

## Features

- **Start Game**: Begin a new game, which resets the board and score.
- **Pause/Resume**: Pause and resume the game with a button toggle.
- **Keyboard Controls**: Control the blocks using the arrow keys:
  - **Left Arrow**: Move block left.
  - **Right Arrow**: Move block right.
  - **Up Arrow**: Rotate the block.
  - **Down Arrow**: Drop the block quickly.
- **Score Tracking**: The score increases as the player clears lines.
- **Game Over Detection**: The game ends when the blocks reach the top of the screen.

## Prerequisites

Before running the Tetris game, ensure you have the following installed:

- **Python 3.x**: The backend is built using Python 3.x, which you can download from the official [Python website](https://www.python.org/).
- **Flask**: A Python web framework used for building the server-side logic.

To install Flask, run the following in your terminal or command prompt:

```bash
pip install flask
```

## Requirements

- **HTML5, CSS3, JavaScript**: For the frontend.
- **Python (Flask)**: For the backend server.
- **Browser**: A modern web browser (such as Chrome, Firefox, or Edge) to run and play the game.

## Using the Program

### Running the Game

1. Clone this repository or download the files to your local system.
2. In the terminal, navigate to the project directory and run the following command to start the Flask server:

```bash
python Tetris.py
```

3. Once the server is running, open a web browser and visit [http://127.0.0.1:5000](http://127.0.0.1:5000).

4. Click the "Start Game" button to begin the game.

### Sample Input and Outputs

#### Start Game

- **Action**: Click the "Start Game" button.
- **Expected Result**: A new game starts with an empty grid and a score of `0`.

#### Move Left

- **Action**: Press the left arrow key (`←`).
- **Expected Result**: The current block moves one space to the left.

#### Move Right

- **Action**: Press the right arrow key (`→`).
- **Expected Result**: The current block moves one space to the right.

#### Rotate Block

- **Action**: Press the up arrow key (`↑`).
- **Expected Result**: The current block rotates 90 degrees.

#### Drop Block

- **Action**: Press the down arrow key (`↓`).
- **Expected Result**: The current block drops to the bottom of the grid.

#### Pause/Resume

- **Action**: Click the "Pause" button.
- **Expected Result**: The game pauses, and the "Pause" button changes to "Resume".
- **Action**: Click the "Resume" button.
- **Expected Result**: The game resumes from where it was paused.

#### Game Over

- **Action**: Blocks reach the top of the grid, preventing any new blocks from being placed.
- **Expected Result**: The game ends, and an alert with the final score is displayed.

---

## Example of Gameplay

1. **Start Game**: You click the "Start Game" button. The game initializes with an empty board and score 0.
2. **Block Falling**: A random block appears at the top center of the grid.
3. **Controls**:
   - You press the **left arrow** to move the block to the left.
   - You press the **down arrow** to make the block fall faster.
   - You press the **up arrow** to rotate the block.
   - The block eventually lands, and new blocks continue to fall.
4. **Clearing Lines**: If a full line of blocks is formed, that line is cleared, and your score increases.
5. **Game Over**: If the blocks stack to the top of the screen, the game ends, and an alert shows your final score.

---

## Screenshots

Below are some screenshots showing the game in action:

### 1. **Game Starting Screen**

!![image](https://github.com/user-attachments/assets/271ad5fc-7ca3-4872-a13b-df9c212fda12)

*Description: The game board at the start of a new game, with the "Start Game" button visible.*

### 2. **Game in Progress**

![image](https://github.com/user-attachments/assets/75ea940b-84c0-418f-b831-8f0d308f7d72)

*Description: A screenshot showing the Tetris grid while blocks are falling. The "Pause" button is also visible.*

### 3. **Game Over Screen**

![image](https://github.com/user-attachments/assets/c76ced68-a10a-423c-8faf-f902aa74e83f)

*Description: The game over screen showing the final score when the blocks reach the top.*

---

## Notes

- The game can be controlled via both keyboard and on-screen buttons.
- The game is built to run locally, meaning you must start the Flask server to play.
- It is recommended to play the game in a browser window that is not too small, so the blocks and controls are visible clearly.

---

## License

This project is open-source and available under the MIT License.
