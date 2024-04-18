# Hangman Game in Python

This is a simple implementation of the classic Hangman game using Python. In this game, players try to guess a secret word by suggesting letters within a certain number of guesses.

## Features

- Randomly selects a word from a predefined list.
- Displays the word as a series of blanks representing each letter.
- Allows the player to guess letters one at a time.
- Tracks the number of incorrect guesses and updates the hangman display accordingly.
- Ends the game when the player guesses the word correctly or runs out of guesses.

## Gameplay
- The game will randomly select a word from the predefined list and display it as a series of blanks (e.g., "_ _ _ _ _").
- You will have a limited number of incorrect guesses (e.g., 6).
- Enter a letter to guess the word. If the letter is in the word, it will reveal all instances of that letter.
- If the letter is not in the word, it will count as an incorrect guess and update the hangman display.
- Continue guessing letters until you either:
- Guess the entire word correctly, winning the game.
- Run out of guesses, losing the game.

## Customization
- You can modify the words list in the hangman.py script to include your own words.
- Adjust the number of maximum incorrect guesses (max_attempts) to make the game easier or more challenging.
