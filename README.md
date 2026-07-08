# 🎮 Number Guessing Game

A simple Python command-line game where the player tries to guess a randomly generated number. The game offers three difficulty levels, validates user input, and provides hints to help the player find the correct number.

---

## 📌 Features

- Three difficulty levels:
  - **Easy:** Numbers from **1–10**
  - **Medium:** Numbers from **11–30**
  - **Hard:** Numbers from **31–60**
- Random number generation using Python's built-in `random` module.
- Input validation for non-numeric values.
- Range validation to ensure guesses stay within the selected difficulty.
- Unlimited attempts until the correct number is guessed.
- Tracks the total number of attempts.
- Hint system:
  - 🔥 **Getting warmer!** if the guess is within 5 numbers of the answer.
  - ❄️ **Freezing cold!** otherwise.
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

```
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

### 2. Navigate to the project folder

```bash
cd number-guessing-game
```

### 3. Run the program

```bash
python game.py
```

> If your system uses Python 3 separately:

```bash
python3 game.py
```

---

## 🎯 Difficulty Levels

| Level | Number Range |
|--------|--------------|
| Easy | 1 – 10 |
| Medium | 11 – 30 |
| Hard | 31 – 60 |

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

---

### Invalid Input

```text
Enter your guess: hello
⚠️ Enter a valid number!
```

---

### Out-of-Range Input

```text
Guess a number between 11 and 30!

Enter your guess: 45
🚫 Guess must be between 11 and 30.
```

---

## 📖 How It Works

1. The player selects a difficulty level.
2. The program generates a random secret number within the chosen range.
3. The player keeps guessing until the correct number is found.
4. After each valid guess, the game:
   - Indicates whether the guess is too high or too low.
   - Provides a proximity hint ("Getting warmer!" or "Freezing cold!").
5. When the correct number is guessed, the program displays the total number of attempts and ends the game.

---

## 📚 Concepts Demonstrated

- Variables
- Dictionaries
- Loops (`while`)
- Conditional statements (`if`, `elif`, `else`)
- Exception handling (`try` / `except`)
- User input validation
- Random number generation
- Functions from Python's standard library

---

## 🚀 Future Improvements

- Limit the number of attempts.
- Add a scoring system.
- Display a leaderboard using file handling.
- Allow replay without restarting the program.
- Add customizable difficulty levels.
- Provide directional hints (e.g., "Very Close").

---

## 👩‍💻 Author

**Sanika Kangane**

If you found this project helpful, consider giving it a ⭐ on GitHub.
