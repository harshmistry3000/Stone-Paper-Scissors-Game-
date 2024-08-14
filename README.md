# Stone-Paper-Scissors-Game-
Stone  🪨  Paper 📰  &amp; Scissors ✂️  Game  ✊🏻 ✌🏻✋🏻 . . . . . 

1. Variables:

- userScore and compScore to track the scores of the user and computer.
- choices to select all game choices (rock, paper, scissors).
- msg for displaying game messages.
- userScorePara and compScorePara to update the displayed scores.

2.Functions:

- genCompChoice(): Randomly generates the computer's choice (rock, paper, or scissors).
- drawGame(): Updates the message and background color when the game is a draw.
- showWinner(userWin, userChoice, compChoice): Updates the score and message based on whether the user won or lost.
- playGame(userChoice): Determines the result of the game by comparing the user's choice with the computer's choice, and calls showWinner or drawGame as appropriate.

3.Event Listeners:

- Each choice button adds an event listener to trigger the playGame function when clicked, passing the user's choice to the function.
