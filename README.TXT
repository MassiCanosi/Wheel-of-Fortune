__Wheel of Fortune Game

Welcome to the Wheel of Fortune game project! This project will guide you through the process of implementing a simplified version of the classic game show, Wheel of Fortune. In this game, players compete to guess a hidden phrase within a specific category, using a spinning wheel to determine their actions and winnings. Let's get started with the rules and instructions.

__Game Rules
Players: The game can have both human and computer players. You can specify the number of human players (num_human) and computer players (num_computer).

Player Money: At the start of the game, every player has $0 in their account.

Player Prizes: Initially, every player has no prizes.

Objective: The goal of the game is to guess a hidden phrase within a given category. For example:

Category: Artist & Song
Phrase: _______ ______' _ ____ ______ ____ ___
Players need to guess the letters and words to reveal the phrase correctly. The case (capitalization) does not matter.

__Gameplay:

Players take turns spinning the wheel to determine a prize amount and perform an action.

If the wheel lands on a cash square, players can do one of the following actions:

Guess any letter that hasn't been guessed by typing a letter (a-z).
Vowels (a, e, i, o, u) cost $250 to guess and can't be guessed if the player doesn't have enough money. All other letters are "free" to guess.
If the guessed letter appears in the phrase, the player wins the cash amount for every occurrence of that letter.
If there is a prize on the wheel, the player also acquires that prize (in addition to any prizes they already have).
If the guessed letter does not appear in the phrase, it becomes the next player's turn.
Example: The player lands on $500 and guesses 'W'. If there are three W's in the phrase, the player wins $1500.

Players can try to guess the complete phrase by typing a phrase (anything over one character that isn't 'pass'). If they guess it correctly, they win the game. If they're incorrect, it's the next player's turn.

Players can pass their turn by entering 'pass'.

If the wheel lands on "lose a turn," the player loses their turn, and the game moves on to the next player.

If the wheel lands on "bankrupt," the player loses their turn and all of their money. However, they keep all the prizes they've won so far.

Winning: The game continues until the entire phrase is revealed, or one player guesses the complete phrase correctly.

__How to Play
Clone or download the repository to your local machine.

Run the game on your preferred Python environment.

Follow the on-screen prompts to set the number of human and computer players, category, and phrase.

Take turns spinning the wheel and making guesses or actions based on the rules mentioned above.

Continue playing until one player reveals the complete phrase or the entire phrase is uncovered.

__Have Fun!
Enjoy playing this simplified version of Wheel of Fortune. Feel free to modify and extend the game to add more features and complexity. If you encounter any issues or have suggestions for improvement, please don't hesitate to provide feedback or contribute to the project. Have a great time playing!
