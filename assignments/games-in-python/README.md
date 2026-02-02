# 📘 Assignment: Games in Python - Hangman

## 🎯 Objective

Build a playable Hangman game in Python to practice string handling, loops, and conditionals. By the end, you will create a text-based game that tracks guesses and determines win/loss outcomes.

## 📝 Tasks

### 🛠️	Game Setup and Word Selection

#### Description
Create the basic game structure and choose a random secret word from a predefined list.

#### Requirements
Completed program should:

- Store a list of possible words
- Randomly select one word at the start of the game
- Initialize the display with underscores for each letter in the word


### 🛠️	Guessing Loop and Win/Loss Logic

#### Description
Implement the main game loop to accept guesses, update the display, and end the game when appropriate.

#### Requirements
Completed program should:

- Prompt the player for a single-letter guess each turn
- Reveal correctly guessed letters in their positions
- Decrease remaining attempts for incorrect guesses
- End with a win message when the word is fully revealed
- End with a loss message when attempts reach zero
