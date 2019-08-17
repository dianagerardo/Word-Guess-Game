### Word Guess Game Pseudocode

1. User clicks a key to start the game.

2. Computer chooses a random value in an array of zoo animals.
make an array zoo animals=[""] and chose at random index0-5

3. Computer turns the word picked out into the same number of dashes as the word length and displays on the screen.

4. User chooses a letter on keyboard to guess the word.
use document.onkeyup to get user input

5. We determine if the user chose the right letter or not.

   * If user picks rock and if computer picks scissors then user wins.
   

   * If user picks rock and if computer picks paper then user loses.

   * If user picks scissors and if computer picks rock then user loses.

   * If user picks scissors and if computer picks paper then user wins.

   * If user picks paper and if computer picks rock then user wins.

   * If user picks paper and if computer picks scissors then user loses.

   * If user picks the same as computer then they tie.

4. We then add to their score.

   * If user wins then we add one to their wins.
    
   * If user loses then we add one to their losses.
    
   * If user ties then we add one to their ties.

5. The user then presses r, p, or s to play again.
