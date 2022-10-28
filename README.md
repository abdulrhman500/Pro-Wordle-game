# Pro-Wordle-game
Logical Programming project using Prolog  for Programming Paradigms course

## The Pro-Wordle game is made up of two main phases:
### 1- knowledge base building phase and
### 2- game play phase.

## In the KB building phase
the player is prompted to enter words with their categories.
Corresponding facts are added to the KB using the predicate word/2 where word(W,C)
is true if W has a category of C. This continues until the player enters done. Below is a
sample of the interaction between the game and the player in the KB building phase

## In the game play phase 
The game displays to the user
the available categories to pick one from. The player is then prompted to pick a length
and category for the word to be guessed. The game picks a word of the given length and
category and the guessing game begins. The player is allowed a maximum number of
guesses equal to the entered length plus one. In each guess, the user must enter a word of
the chosen length. The game then displays to the user the correctly entered letters (not
necessarily in correct positions), and the correctly entered letters in correct positions.
Below is a sample of the interaction between the game and the player in the game play
phase based on the example KB provided earlier


![Capture](https://user-images.githubusercontent.com/75482475/198693028-513e9aaf-dbb9-430c-9e02-8f8def9481ca.PNG)
