# Python-Beginner-Game

# (1)Number Guessing Game

This is a simple console-based Number Guessing Game implemented in Python. The program generates a random number between 1 and 100, and the player has to guess the correct number within a limited number of attempts.

## Features

- **Modular Structure:** The code is organized into functions for better readability and maintainability.
- **User Input Handling:** The program utilizes input validation to ensure the user enters a valid integer for their guesses.
- **Dynamic Feedback:** Provides dynamic feedback for each guess, guiding the user to the correct answer.
- **Random Number Generation:** Uses Python's `random` module to generate a random number for each game.
- **Functions and Flow Control:** Demonstrates the use of functions and flow control structures in Python.

## Getting Started

### Prerequisites

- Python 3.x installed on your machine.

### How to Run

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/number-guessing-game.git
   ```

2. Navigate to the project directory:

   ```bash
   cd number-guessing-game
   ```

3. Run the Python script:

   ```bash
   python number_guessing_game.py
   ```

4. Follow the on-screen prompts to enter your name and play the game.

## Code Structure

The code is structured as follows:

- **`main()` Function:** Orchestrates the flow of the program, calling other functions as needed.
- **User Interaction Functions:** Functions responsible for interacting with the user, such as `get_player_name()`, `greet_player()`, and `ask_to_play_game()`.
- **Game Logic Function:** The core of the game is implemented in the `play_guessing_game()` function, handling the random number generation, user guesses, and feedback.

