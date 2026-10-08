# Guess the Number Game

## Project Overview

This project is a simple interactive Guess the Number game developed using Python.

The computer randomly generates a number between 1 and 100, and the player has three attempts to guess the correct number. After each incorrect guess, the game provides a hint telling the player whether their guess was too high or too low.

The game also keeps track of the player's statistics and allows the player to start another round after completing a game.

---

## Objective

The objective of the game is to correctly guess the randomly generated number within three attempts.

---

## How to Play

1. Start the game.
2. The computer generates a random number between 1 and 100.
3. Enter your guess when prompted.
4. The game will tell you whether your guess is:
   - Too high
   - Too low
   - Correct
5. You have a maximum of three attempts.
6. If you guess the number correctly, you win the game.
7. If you use all three attempts without guessing correctly, the game ends and the correct number is revealed.
8. After the game, you can choose whether to play another round.
9. When you choose to stop playing, your statistics are displayed.

---

## Input Validation

The game includes input validation to prevent invalid inputs from causing the program to crash.

### Guess Validation

The player must enter a number between 1 and 100.

For example:

    Enter your guess: hi
    Invalid input. Please enter a number.

If the player enters a number outside the allowed range:

    Enter your guess: 150
    Please enter a number between 1 and 100.

The player is then asked to enter another guess.

### Play Again Validation

After each game, the player is asked whether they want to play again.

The player must enter either:

    yes

or:

    no

If another response is entered, the game asks the player to enter a valid response.

---

## Game Statistics

The game keeps track of the player's performance using global counters.

The statistics include:

- Games played
- Games won
- Games lost
- Win rate

The win rate is calculated using:

    Win Rate = (Games Won / Games Played) × 100

---

## Python Concepts Used

This project demonstrates several fundamental Python programming concepts, including:

- Variables
- Global variables
- Functions
- if, elif and else statements
- while loops
- User input
- Input validation
- try and except error handling
- Random number generation
- Counters
- Basic mathematical calculations
- Comments and documentation

The random module is used to generate the secret number.

---

## Functions

The game uses several functions to organise the code.

### get_guess()

This function asks the player for their guess and checks that the input is a valid number between 1 and 100.

### play_game()

This function runs one complete round of the game. It generates the random number, manages the attempts, checks the player's guesses and updates the game statistics.

### display_statistics()

This function displays the player's statistics, including games played, games won, games lost and win rate.

---

## How to Run the Game

The game is provided as a Jupyter Notebook.

To run the game:

1. Open the Jupyter Notebook.
2. Run the code cells from the top in order.
3. Follow the instructions displayed in the notebook.
4. Enter your guesses when prompted.
5. Choose whether to play another round when asked.
6. The statistics will be displayed when you choose to stop playing.

---

## Project Files

The project contains:

- `Guess_The_Number_Game.ipynb` – The Python game and source code.
- `README.md` – Instructions and information about the project.
- `Flowchart.png` – Flowchart showing the game's logic.

---

## Project Features

- Randomly generated numbers
- Three attempts per game
- Too high / too low hints
- Input validation
- Error handling
- Win and loss tracking
- Game statistics
- Win rate calculation
- Play-again functionality
- Clear instructions and feedback

---

## Author

Lucille's Python Game Development Project
