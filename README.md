````markdown
# Number Guessing Game

A simple command-line game built with Python where the player selects a difficulty level and tries to guess a randomly generated number. The game provides warm/cold hints based on how close the guess is and tracks the total number of attempts.

---

## Features

- Three difficulty levels
- Random number generation
- Input validation
- Range validation
- Warm/Cold hint system
- Attempt counter

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| Python 3 | Programming Language |
| `random` | Generate random numbers |

---

## Project Structure

```text
Number-Guessing-Game/
│
├── game.py
└── README.md
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Number-Guessing-Game.git
```

> Replace `your-username` with your GitHub username after creating the repository.

### 2. Navigate to the project directory

```bash
cd Number-Guessing-Game
```

### 3. Run the game

```bash
python game.py
```

---

## Difficulty Levels

| Level | Range |
|-------|-------|
| Easy | 1 – 10 |
| Medium | 11 – 30 |
| Hard | 31 – 60 |

---

## Sample Output

### Example 1 – Correct Guess

```text
🎮 Guess My Number Game!
1️=Easy, 2️=Medium, 3️=Hard: 1

Guess a number between 1 and 10!

Enter your guess: 4
Too low! Go higher.
🔥 Getting warmer!

Enter your guess: 6
🎉 Correct! You guessed it in 2 tries!

👏 Good game!
```

---

### Example 2 – Invalid Input

```text
🎮 Guess My Number Game!
1️=Easy, 2️=Medium, 3️=Hard: 2

Guess a number between 11 and 30!

Enter your guess: hello
⚠️ Enter a valid number!

Enter your guess: 35
🚫 Guess must be between 11 and 30.

Enter your guess: 22
Too high! Go lower.
❄️ Freezing cold!
```

---

### Example 3 – Hard Level

```text
🎮 Guess My Number Game!
1️=Easy, 2️=Medium, 3️=Hard: 3

Guess a number between 31 and 60!

Enter your guess: 40
Too low! Go higher.
❄️ Freezing cold!

Enter your guess: 48
Too high! Go lower.
🔥 Getting warmer!

Enter your guess: 46
🎉 Correct! You guessed it in 3 tries!

👏 Good game!
```

> **Note:** The secret number is randomly generated every time the game runs, so your output will vary.

---

## Game Flow

```text
Start
  │
  ▼
Select Difficulty
  │
  ▼
Generate Random Number
  │
  ▼
Enter Guess
  │
  ├── Invalid Input ─────► Enter Again
  ├── Out of Range ──────► Enter Again
  ├── Too Low ───────────► Show Hint → Guess Again
  ├── Too High ──────────► Show Hint → Guess Again
  └── Correct Guess
          │
          ▼
   Display Attempts
          │
          ▼
       End Game
```

---

## Future Improvements

- Add a replay option
- Add limited attempts
- Implement a scoring system
- Store the best score
- Add a timer mode
- Support custom difficulty levels

---

## Author

**Sanika Kangane**

B.Tech Computer Science Engineering Student  
ITM Skills University

---

If you found this project helpful, consider giving it a ⭐ on GitHub.
````
