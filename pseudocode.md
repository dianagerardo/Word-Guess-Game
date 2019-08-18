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



<!-- Choose a theme for your game! In the demo, we picked an 80s theme: 80s questions, 80s sound and an 80s aesthetic. You can choose any subject for your theme, though, so be creative! -->

    <!-- Theme will be a zoo -->
    <!-- I will add pictures of zoo animals that they can guess from the array I include with the word game guess choices  and every time they get a word right the game will play that animals sounds-->

     <!-- My array of zoo animals.
    var zooAnimals = [" Zebra", "Rhino" , "Giraffe" , "Lion" ]; // Prints 4 to the console because there are 4 items in
        our zooAnimals array. console.log(zooAnimals.length); // Prints Rhino to the console. Remember, the first item
        in an array has an index position of 0! console.log(zooAnimals[1]); // Prints undefined... because the last
        index ("Owl") is 3. console.log(zooAnimals[4]); // Converts the user's answer to lowercase. var
        userGuessLower=userGuess.toLowerCase();  When a player presses a key the game will start. I will include an 
        on.click event -->

<!-- Press any key to get started! should be displayed on the screen to start-->

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


    <!-- Loop through the array to pick a random animal word -->
<!-- 
    // Creating an array of vegetables.
    var vegetables = ["Carrots", "Peas", "Lettuce", "Tomatoes"];

    // Looping through each item in the array and logging a message to the console.
    for (var i = 0; i < vegetables.length; i++) { console.log("I love " + vegetables[i]);
} -->

<!-- Make the word into a string array -->

<!-- console.log(studentsRow1[3].split("")); -->

<!-- Overwrite the array word picked with dashes for each letter -->

<!-- // We can either overwrite each element of the array to make it lowercase, or we can use the toLowerCase() method.
drinks[0] = " coke"; drinks[1]="pepsi" ; drinks[2]="water" ; drinks[3]=drinks[3].toLowerCase(); // Logging our new
        array to the console. console.log("Second statement"); console.log(drinks[0]); console.log(drinks[1]);
        console.log(drinks[2]); console.log(drinks[3]); 
        
        
        OR 
        
        public class Program { public static void main(String[] args)
        { String value="java" ; char[] array=value.toCharArray(); // Convert string to a char array. for(int i=0; i <
        value.length(); i++) { array[i]='-' ; } // Loop over chars in the array. for (char c : array) {
        System.out.print(c); } } } 
        
        Check each letter the user picks against the word -->

        // This is our starting myFarm array.
        var myFarm = ["chickens", "pigs", "cows", "horses", "ostriches"];

        // Creating a variable to hold our array length.
        var arrayLength = myFarm.length;

        // Looping through our myFarm array.
        for (var j = 0; j < arrayLength; j++) { // Console out the farm animal in the current index.
            console.log(myFarm[j]); // If the first character in the current animal is "c" or "o" , alert the following
            message. if (myFarm[j].charAt(0)==="c" || myFarm[j].charAt(0)==="o" ) { alert("Starts with a c or an o!"); }
            } <!-- 3. Use key events to listen for the letters that your players will type. -->

            When the user clicks on a key the key pressed should be checked against the letters available, if they match
            === then display the letter

            // Created a prompt to get the user's favorite band.
            var userGuess = prompt("Which band or artist do you like?");

            // Converts the user's answer to lowercase.
            var userGuessLower = userGuess.toLowerCase();

            // Now we check the myBands array to see if it contains the user's answer.
            // If the user's band is not in the array...
            if (myBands.indexOf(userGuessLower) === -1) {
            alert("Nah! They're pretty lame...");
            }
            // If it is in the array...
            else {
            alert("OMG! I love them too!");
            }

            //
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


