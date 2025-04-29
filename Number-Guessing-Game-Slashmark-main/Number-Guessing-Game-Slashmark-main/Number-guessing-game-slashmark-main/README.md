# Number-guessing-game-slashmark

**README.md** file for your new Python game with detailed instructions on how to run and play it.

---

## 🎮 Number Guessing Game

This is a simple **number guessing game** implemented in Python. The game generates a random number between 1 and 200, and the player has 6 chances to guess it correctly.

---

## 📂 File Structure

```
/number-guessing-game
├── guessing_game.py  # Main script for the number guessing game
└── README.md         # Project documentation
```

---

## 🚀 Features

- 🎯 **Random Number Generation:** Generates a random number between 1 and 200.

- 🕹️ **Limited Attempts:** Players get 6 chances to guess the number.
  
- 💬 **Helpful Hints:** Informs the player if their guess is too high or too low.
  
- 🏆 **Win/Lose Messages:** Provides feedback if the player wins or loses.
  
- 🔁 **Play Again Option:** Allows the player to replay the game.

---

## ⚡️ Prerequisites

Before running the application, ensure you have the following:

- Python 3.x installed on your system.  
To check if Python is installed, run:
```bash
python --version
```
If not installed, download and install it from [Python Official Website](https://www.python.org/downloads/).

---

## 📖 How to Run

Follow these steps to execute the `guessing_game.py` file:

### 1. Clone the Repository
```bash
https://github.com/PSaiPrathap/Number-guessing-game-slashmark
```
Replace `your-username` and `your-repository-name` with your GitHub username and repository name.

### 2. Navigate to the Project Directory
```bash
cd your-repository-name
```

### 3. Run the Application
Run the `guessing_game.py` script using Python:
```bash
python guessing_game.py
```

---

## 📝 Usage Instructions

1. **Start the Game:** Run the script and enter your name.
2. **Make Your Guess:** Guess a number between 1 and 200.
3. **Hints Provided:**
    - If your guess is too low, the game will inform you.
    - If your guess is too high, the game will let you know.
4. **Win/Loss Outcome:**
    - If you guess the correct number, you win!
    - If you don't guess correctly within 6 attempts, the correct number is revealed.
5. **Play Again:** You will be prompted to play again.

---

## 📌 Example Usage

```
May I ask you for your name?
John
John, we are going to play a game. I am thinking of a number between 1 and 200
Go ahead. Guess!
Guess: 50
The guess of the number that you have entered is too low
Try Again!
Guess: 120
The guess of the number that you have entered is too high
Try Again!
Guess: 90
Good job, John! You guessed my number in 3 guesses!
Do you want to play again?
```

---

## ⚙️ Code Overview

- `intro()` – Asks for the player’s name and introduces the game.
- `pick()` – Handles the guessing logic:
  - Takes the player’s guess.
  - Checks if the guess is in range and provides hints.
  - Allows 6 guesses and ends the game if the number is not guessed.
- `playagain` – Allows the player to restart the game.

