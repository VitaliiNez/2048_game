# Project Description: 2048 Game

## Overview

This project is a web-based implementation of the popular 2048 game. The game involves sliding numbered tiles on a grid to combine them and create a tile with the number 2048. The project is built using HTML tables for the game board layout and JavaScript for the game logic.

## Technologies Used

The 2048 game is built using modern web technologies to ensure a responsive and engaging user experience. The key technologies utilized are:

- **HTML:** The game board is constructed using a table element, with each cell representing a tile space. This approach simplifies the layout and makes it easy to style and update the game board.
- **CSS:** Basic styling is applied to the table and its cells to create a visually appealing game board. This includes colors and fonts for tile movements and merges.
- **JavaScript:** The game logic is divided into multiple JavaScript files, ensuring a modular and maintainable codebase. Key components include game initialization, user input handling, and game state update.

## How to Play

1. **Start the Game:** Open the game in a web browser. The game board will initialize with two random tiles.
2. **Move Tiles:** Use the arrow keys on your keyboard to move the tiles in the desired direction. Tiles will slide until they collide with another tile or the edge of the board.
3. **Combine Tiles:** When two tiles with the same number collide, they merge into one tile with their sum. The goal is to combine tiles to create a tile with the number 2048.
4. **Game Over:** The game ends when no more moves are possible. The final score is displayed, and players can start a new game to try again.

## Running the Project Locally

To run the 2048 game project locally, follow these steps:

1. **Clone the Repository:**
   `git clone https://github.com/VitaliiNez/2048_game.git`
2. **Navigate into the Project Directory:**
   `cd 2048_game`
3. **Ensure Node.js Version:**
   The project requires Node.js version 14.21.3 to run. You can check your Node.js version with:
   `node -v`
   If necessary, use a version manager like [nvm](https://github.com/nvm-sh/nvm/) to install and switch to the correct version.
4. **Install Dependencies:**
   `npm install`
5. **Run the Project:**
   `npm start`

You can now play the 2048 Game locally in your browser.

To access the live site, visit [2048 Game](https://VitaliiNez.github.io/2048_game/).
