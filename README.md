Simon Game Challenge
-------------------------------------
Simon Game Challenge is a web-based game that tests your memory and pattern recognition skills. The game generates a random sequence of colors, which the player must repeat in the same order to progress to the next level.

![simo9](https://github.com/VaishnaviSingh1/Simon-Game-Challange/assets/98222001/d63abdee-8284-4cbb-82b2-989a492fa244)


Features
------------------

1. Generates a random sequence of colors each round.
2. Users must repeat the sequence to advance to higher levels.
3. Provides visual and audio feedback for user interactions and game progress.
4. Displays game over message and restarts the game upon user input after a wrong sequence.

How to Play
-------------------

1. Press any key to start the game.
2. Watch the sequence of colors displayed.
3. Click the buttons to repeat the sequence in the same order.
4. Progress through levels by successfully repeating the sequences.
6. The game ends if a wrong button is pressed. Restart by pressing any key.

Files
---------------
1. index.html: The main HTML file containing the game layout.
2. styles.css: The CSS file for styling the game.
3. game.js: The JavaScript file containing the game logic.
4. sounds/: Directory containing sound files for game feedback.

Game Logic Overview
------------------------------
game.js

1. Defines the color sequence and user input arrays.
2. Tracks the game's state and current level.
3. Uses jQuery to handle user interactions and game events.

Functions:
-------------------

1. nextSequence(): Generates the next color in the sequence.
2. checkAnswer(): Verifies user input against the game sequence.
3. playSound(): Plays the corresponding sound for each color.
4. animatePress(): Adds a visual effect when buttons are pressed.
5. startOver(): Resets the game state after a game over.


Sound Files
-------------------------------------

1. sounds/blue.mp3: Sound for the blue button.
2. sounds/green.mp3: Sound for the green button.
3. sounds/red.mp3: Sound for the red button.
4. sounds/yellow.mp3: Sound for the yellow button.
5. sounds/wrong.mp3: Sound for incorrect user input.


Clone the repository:
-------------------------------
```
git clone https:https://github.com/VaishnaviSingh1/Simon-Game-Challange.git
```

*Ensure the sounds/ directory is in the same location as index.html.*
*Open index.html in your web browser to start the game.*

Requirements
----------------------
1. A web browser with JavaScript enabled.
2. Internet connection to load jQuery from CDN.
