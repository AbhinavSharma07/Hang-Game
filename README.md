# Hangman Game

This is a classic implementation of the Hangman game in Python. Players can guess letters to uncover a hidden word, and a hangman figure is drawn for each incorrect guess.

## How to Play--

1. Run the `hangman.py` script in a Python environment.
2. Follow the prompts to guess letters and uncover the hidden word.
3. For each incorrect guess, a part of the hangman figure is drawn.
4. The game ends when either the player guesses the word or the hangman figure is completed.

## Features

- Randomly selects words to guess from a predefined list.
- Visual representation of the hangman figure for incorrect guesses.
- Option to play the game again after completion.

## Requirements

- Python 3.x
- No additional libraries are required.

## How to Run

1. Clone the repository or download the `hangman.py` script.
2. Open a terminal/command prompt.
3. Navigate to the directory containing the `hangman.py` script.
4. Run the script using the command: `python hangman.py`.

## Example Gameplay

```plaintext
Welcome to Hangman game by Abhinav

Enter your name: Player1
Hello Player1! Best of Luck!
The game is about to start!
Let's play Hangman!

This is the Hangman Word: _ _ _ _ _ _ Enter your guess:
a
_ _ _ _ a _ 
This is the Hangman Word: _ _ _ _ a _ Enter your guess:
e
_ _ _ _ a _ 
This is the Hangman Word: _ _ _ _ a _ Enter your guess:
i
_ i _ _ a _ 
This is the Hangman Word: _ i _ _ a _ Enter your guess:
o
_ i _ _ a _ 
This is the Hangman Word: _ i _ _ a _ Enter your guess:
u
_ i _ _ a _ 
This is the Hangman Word: _ i _ _ a _ Enter your guess:
t
_ i _ t a _ 
This is the Hangman Word: _ i _ t a _ Enter your guess:
s
_ i _ t a _ 
This is the Hangman Word: _ i _ t a _ Enter your guess:
n
n i _ t a _ 
This is the Hangman Word: n i _ t a _ Enter your guess:
r
n i _ t a r 
Congrats! You have guessed the word correctly!
Do You want to play again? y = yes, n = no 
n
Thanks For Playing! We expect you back again!
