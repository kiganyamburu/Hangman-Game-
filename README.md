## Hangman Game
This is a simple Hangman game implemented in Python. The game randomly selects a word from a list of words, and the player has to guess the word letter by letter. The game keeps track of the letters guessed and the lives remaining. If the player guesses all the letters of the word before running out of lives, they win. Otherwise, they lose.

## Game Setup
To run the game, simply execute the Python script. The game will display the Hangman logo and a series of underscores representing the letters of the randomly selected word.

## Gameplay
The player is prompted to guess a letter. The game checks if the letter has already been guessed. If it has, the game will display a message indicating this. If the letter is in the word, the game will reveal the letter in the correct positions. If the letter is not in the word, the game will deduct a life from the player and display a message indicating this.

The game continues until the player has guessed all the letters of the word or has run out of lives.

## Game Over
If the player guesses all the letters of the word before running out of lives, the game will display a message indicating that they have won. If the player runs out of lives before guessing all the letters of the word, the game will display a message indicating that they have lost.

## Credits
The Hangman logo and the stages of the Hangman are taken from the hangman_art.py module. The list of words is taken from the hangman_words.py module.The game logic is implemented in the hangman.py module.

## License
This project is licensed under the MIT
