Game Name: Guess the Fruit


<img width="849" alt="Screen Shot 2025-05-02 at 6 03 25 PM" src="https://github.com/user-attachments/assets/cc96515a-0f5c-4e4b-92cd-6e106469e5db" />


Technologies used: JavaScript, HTML, CSS


GitHub repo link: <https://github.com/ShahlaaBee/Browser-Based-Game-Project-Shahlaa>


Deployed project link: https://shahlaabee.github.io/Browser-Based-Game-Project-Shahlaa/


Next steps: Adding sounds and selecting letters using the keyboard instead of just clicking on the letter.


User story:

As a user, I want to see a landing page with the game name and an engaging image when I arrive at the website.

As a user, I want to see blanks where letters can be inserted.

As a user, I want to see buttons for all 26 alphabets (English characters).

As a user, I want to be able to click on the alphabet button.

As a user, I want the alphabet to be transferred to the given blank if the answer is correct.

As a user, I want visual feedback after a wrong selection represented in the change of "attempts left".

As a user, I want to see the number of attempts allowed before I lose the game.

As a user, I want to be given a clear message that I won once all correct letters are inserted.

As a user, I want the winning message to include the number of wrong attempts I had.

As a user, I want to be given a clear message that I lost once I exhausted all attempts.

As a user, I want to see a button to try again after I win or lose.


Pseudocode:

// 1) Variables used to track the state of the game:

//    The player choice of alphabet

//    A result message - display if player won or lost along with the number of attempts they had

//   Number of attempts left after every wrong attempt

//   Try again button


// 2) Required constants:

//    There are 26 choices a user can make (“A”, …, “Z”)

//    There is 1 result message

//    There is a message indicating the number of wrong attempts left

//    There is a "try again" button

//    We'll need a reference to a DOM element to display messages
 

// 3) Handle a player clicking a button

// 4) Handle generating random word selections for the computer player

// 5) Render win/lose messages for the computer player

// 6) Clearly indicate number of trials left in the game

// 7) Render a "try again" button after a winning or losing game

// 8) Render an "incorrect" sign after a wrong choice of letter
