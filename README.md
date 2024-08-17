Tic-Tac-Toe React Game
This is a simple yet engaging Tic-Tac-Toe game built using React, JavaScript, HTML, and CSS. This project was created as a learning exercise in React, where I explored and applied key concepts such as components, props, useState, hooks, and state management.

Features
Interactive Player Names: Players can edit their names, making the game more personalized.
Active Player Highlighting: The current player’s name is highlighted during their turn, making it easy to track whose move it is.
Game Board: A dynamic game board that updates in real-time as players make their moves.
Game Over Screen: Displays when a player wins or the game ends in a draw, with an option to restart the game.
Move Logs: A log section to keep track of each move made by the players, showing which player played which move and when.
Components
Player Component
The Player component allows users to change player names and indicates which player is currently active by highlighting their name.

GameBoard Component
The GameBoard component renders the 3x3 grid and handles the placement of X’s and O’s as the game progresses.

GameOver Component
The GameOver component appears when the game is over, showing either the winner or indicating a draw. It also provides a button to restart the game.

Log Component
The Log component tracks and displays a history of moves, allowing players to see the progression of the game.

Winning Combinations
The game uses a predefined set of winning combinations stored in the winning-combinations.js file to check for a win after every move.

How It Works
Turn Management: The game alternates turns between Player 1 (X) and Player 2 (O). The active player is determined based on the number of moves made.
Winner Determination: After each move, the game checks for any winning combination. If a player achieves one, they are declared the winner.
Draw Condition: If all squares are filled without a winner, the game ends in a draw.
Restarting the Game: Players can restart the game at any time, resetting the board and the move log.
How to Run the Project
To run this project locally:

Clone the repository:

bash
Copy code
git clone https://github.com/mayank2021264/tic-tac-toe_React.git
Navigate to the project directory:

bash
Copy code
cd tic-tac-toe_React
Install the dependencies:

bash
Copy code
npm install
Run the development server:

bash
Copy code
npm start
Build the project for production:

bash
Copy code
npm run build
Deploy:
You can deploy this project to any hosting platform that supports static sites, like Netlify, Vercel, or GitHub Pages.

Conclusion
This project was a great opportunity to dive into React and get hands-on experience with the basics. The game is fully functional, responsive, and provides an enjoyable user experience with the added features of editable player names, move logs, and an intuitive game over screen.
