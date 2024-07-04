Simon Game Challenge
-------------------------------------
Simon Game Challenge is a web-based game that tests your memory and pattern recognition skills. The game generates a random sequence of colors, which the player must repeat in the same order to progress to the next level.

Features
------------------

-Generates a random sequence of colors each round.
-Users must repeat the sequence to advance to higher levels.
-Provides visual and audio feedback for user interactions and game progress.
-Displays game over message and restarts the game upon user input after a wrong sequence.

How to Play
-------------------

-Press any key to start the game.
-Watch the sequence of colors displayed.
-Click the buttons to repeat the sequence in the same order.
-Progress through levels by successfully repeating the sequences.
-The game ends if a wrong button is pressed. Restart by pressing any key.

Files
---------------
-index.html: The main HTML file containing the game layout.
-styles.css: The CSS file for styling the game.
-game.js: The JavaScript file containing the game logic.
-sounds/: Directory containing sound files for game feedback.

Game Logic Overview
------------------------------
game.js

-Defines the color sequence and user input arrays.
-Tracks the game's state and current level.
-Uses jQuery to handle user interactions and game events.

Functions:
-------------------

-nextSequence(): Generates the next color in the sequence.
-checkAnswer(): Verifies user input against the game sequence.
-playSound(): Plays the corresponding sound for each color.
-animatePress(): Adds a visual effect when buttons are pressed.
-startOver(): Resets the game state after a game over.


Sound Files
-------------------------------------

-sounds/blue.mp3: Sound for the blue button.
-sounds/green.mp3: Sound for the green button.
-sounds/red.mp3: Sound for the red button.
-sounds/yellow.mp3: Sound for the yellow button.
-sounds/wrong.mp3: Sound for incorrect user input.
-Setup

Clone the repository:
-------------------------------

git clone https://github.com/your-username/simon-game-challenge.git

*Ensure the sounds/ directory is in the same location as index.html.*
*Open index.html in your web browser to start the game.*

Requirements
----------------------
-A web browser with JavaScript enabled.
-Internet connection to load jQuery from CDN.
