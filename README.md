# Random Number Guessing Game

## Project Description
This Python project is a simple command-line game where the user tries to guess a randomly generated number. The program provides feedback after each guess, indicating whether the guess is too high, too low, or correct. It also tracks the number of attempts the user has made and displays the total number of guesses once the correct number is guessed.

## Features
- Randomly generates a number between 1 and 100.
- Provides feedback for each guess:
  - "Too high" if the guess is greater than the number.
  - "Too low" if the guess is lower than the number.
  - "Correct" when the user guesses the right number.
- Tracks the number of guesses made by the user.
- Ends the game once the correct number is guessed.

## How It Works
1. The program generates a random number between 1 and 100 using the `random` module.
2. The user is prompted to input their guess via the command line.
3. The program compares the guess with the randomly generated number and provides feedback accordingly.
4. The game continues until the user guesses the correct number.
5. After the correct guess, the program displays the total number of attempts made by the user.

## Requirements
- Python 3.x

## How to Run the Game
1. Clone or download the project.
2. Open a terminal or command prompt in the project directory.
3. Run the following command:
   ```bash
   python guess_number.py
