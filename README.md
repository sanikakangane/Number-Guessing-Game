# 🎮 Number Guessing Game

A simple command-line Python game where the player attempts to guess a randomly generated number. The game offers three difficulty levels, validates user input, provides helpful hints, and tracks the number of attempts taken to guess the correct number.



---

## 📌 Features

- Three difficulty levels:
  - **Easy:** Numbers from **1 – 10**
  - **Medium:** Numbers from **11 – 30**
  - **Hard:** Numbers from **31 – 60**

- Random number generation using Python's built-in `random` module.

- Input validation for non-numeric values.

- Range validation to ensure guesses stay within the selected difficulty.

- Unlimited attempts until the correct number is guessed.

- Tracks the total number of attempts.

- Hint system:
  - 🔥 **Getting warmer!** — when the guess is within **5 numbers** of the secret number.
  - ❄️ **Freezing cold!** — otherwise.

- Feedback after every guess:
  - Too high
  - Too low
  - Correct guess



---

## 🛠️ Technologies Used

- Python 3
- Built-in `random` module



---

## 📂 Project Structure

```text
.
├── game.py
└── README.md
```



---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/number-guessing-game.git
```

### 2. Move into the project folder

```bash
cd number-guessing-game
```

### 3. Run the game

```bash
python game.py
```

If your system uses Python 3 separately:

```bash
python3 game.py
```



---

## 🎯 Difficulty Levels

| Level | Number Range |
| :--- | :--- |
| Easy | **1 – 10** |
| Medium | **11 – 30** |
| Hard | **31 – 60** |



---

## 💻 Sample Output

### Easy Mode

```text
🎮 Guess My Number Game!

1=Easy, 2=Medium, 3=Hard: 1

Guess a number between 1 and 10!

Enter your guess: 5
Too low! Go higher.
Getting warmer! 🔥

Enter your guess: 8
Too high! Go lower.
Getting warmer! 🔥

Enter your guess: 7
🎉 Correct! You guessed it in 3 tries!

👏 Good game!
```

### Invalid Input

```text
Enter your guess: hello

⚠️ Enter a valid number!
```

### Out-of-Range Input

```text
Guess a number between 11 and 30!

Enter your guess: 45

🚫 Guess must be between 11 and 30.
```



---

## 📖 How It Works

1. The player selects a difficulty level.

2. The program generates a random number within the selected range.

3. The player enters guesses until the correct number is found.

4. After each valid guess, the game:
   - Indicates whether the guess is **too high** or **too low**.
   - Displays a proximity hint:
     - 🔥 Getting warmer!
     - ❄️ Freezing cold!

5. Once the correct number is guessed, the program displays the total number of attempts and ends the game.



---

## 📚 Concepts Demonstrated

- Variables

- Dictionaries

- `while` loops

- Conditional statements (`if`, `elif`, `else`)

- Exception handling (`try` / `except`)

- User input validation

- Random number generation

- Standard library usage



---

## 🚀 Future Improvements

- Add a limited-attempt mode.

- Introduce a scoring system.

- Save high scores using file handling.

- Allow users to replay without restarting the program.

- Add customizable difficulty levels.

- Include additional hint types.



---

## 👩‍💻 Author

**Sanika Kangane**

If you like this project, consider giving it a ⭐ on GitHub!
