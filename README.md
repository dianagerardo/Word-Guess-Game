# Word-Guess-Game
### Word Guess Game Pseudocode

1. User clicks a key to start the game.

2. Computer chooses a random value in an array of zoo animals.
make an array zoo animals=[""] and chose at random index0-5

3. Computer turns the word picked out into the same number of dashes as the word length and displays on the screen.

4. User chooses a letter on keyboard to guess the word.
use document.onkeyup to get user input

5. We determine if the user chose the right letter or not.

4. We then add letters to their word.

   * If user wins then it displays win message.
    
   * If user loses then it displays game over!

5. The user then presses restart to try again.


Choose a theme for your game! In the demo, we picked an 80s theme: 80s questions, 80s sound and an 80s aesthetic. You can choose any subject for your theme, though, so be creative!

Theme will be a zoo 
I will add pictures of zoo animals that they can guess from the array I include with the word game guess choices  and every time they get a word right the game will play that animals sounds

     <!-- My array of zoo animals.
    var zooAnimals = [" Zebra", "Rhino" , "Giraffe" , "Lion" ]; // Prints 4 to the console because there are 4 items in
        our zooAnimals array. console.log(zooAnimals.length); // Prints Rhino to the console. Remember, the first item
        in an array has an index position of 0! console.log(zooAnimals[1]); // Prints undefined... because the last
        index ("Owl") is 3. console.log(zooAnimals[4]); // Converts the user's answer to lowercase. var
        userGuessLower=userGuess.toLowerCase();  When a player presses a key the game will start. I will include an 
        on.click event -->

Press any key to get started! should be displayed on the screen to start

    <!-- <body>
        <div class="container">
          <div class="row">
            <div class="col-md-offset-2 col-md-8">
              <div class="jumbotron">
                <h2>You just typed <span id="user-text"><strong>...Nothing.</strong></span></h2>
              </div>
            </div>
          </div>
        </div> -->

    <!-- We have to put this at the end of our document to ensure the user-text
             span exists when we try to access it. -->
    <!-- <script type="text/javascript">
          // Let's start by grabbing a reference to the <span> below.
          var userText = document.getElementById("user-text");
    
          // Next, we give JavaScript a function to execute when onkeyup event fires.
          document.onkeyup = function(event) {
            userText.textContent = event.key;
          }; -->

Loop through the array to pick a random animal word 
    // Creating an array of vegetables.
    var vegetables = ["Carrots", "Peas", "Lettuce", "Tomatoes"];

    // Looping through each item in the array and logging a message to the console.
    for (var i = 0; i < vegetables.length; i++) { console.log("I love " + vegetables[i]);
}

Make the word into a string array

Overwrite the array word picked with dashes for each letter 


            <!-- 4. Display the following on the page: -->

            // 5. Press any key to get started!

            // 6. Wins: (# of times user guessed the word correctly).

            // * If the word is `madonna`, display it like this when the game starts: `_ _ _ _ _ _ _`.

            // * As the user guesses the correct letters, reveal them: `m a d o _ _ a`.

            // 7. Number of Guesses Remaining: (# of guesses remaining for the user).

            // 8. Letters Already Guessed: (Letters the user has guessed, displayed like `L Z Y H`).

            // 9. After the user wins/loses the game should automatically choose another word and make the user play it.

            // ##### Word Guess Game Bonuses

            // 1. Play a sound or song when the user guesses their word correctly, like in our demo.
            // 2. Write some stylish CSS rules to make a design that fits your game's theme.
            // 3. **HARD MODE:** Organize your game code as an object, except for the key events to get the letter
            guessed. This will be a challenge if you haven't coded with JavaScript before, but we encourage anyone
            already familiar with the language to try this out.
            // 4. Save your whole game and its properties in an object.
            // 5. Save any of your game's functions as methods, and call them underneath your object declaration using
            event listeners.
            // 6. Don't forget to place your global variables and functions above your object.
            // * Remember: global variables, then objects, then calls.
            // 7. Definitely talk with a TA or your instructor if you get tripped up during this challenge. -->


