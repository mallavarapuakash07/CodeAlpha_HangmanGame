# CodeAlpha_HangmanGame

> **CodeAlpha Internship Project – Task 1:** A Python-based command-line Hangman game that randomly selects a word and allows users to guess it letter by letter with a maximum of six incorrect attempts.

# 🎮 Hangman Game – CodeAlpha Internship Project

## 📌 Project Overview

This project is a **simple command-line Hangman game developed in Python** as part of my **CodeAlpha Internship**.

The game randomly selects a word from a predefined list, and the player has to guess the word one letter at a time. The player gets a maximum of **6 incorrect guesses** before the game ends.

This project was developed to practice and demonstrate fundamental Python programming concepts such as loops, conditional statements, lists, user input, string manipulation, and the `random` module.

## 🎯 Objective

The main objective of this project is to create an interactive Hangman game where:

* A word is selected randomly.
* The player guesses the word one letter at a time.
* Correctly guessed letters are displayed.
* Incorrect guesses are counted.
* The player gets a maximum of 6 incorrect attempts.
* The game displays whether the player wins or loses.

## ✨ Features

* 🎲 Random word selection
* 🔤 Letter-by-letter guessing
* ❤️ Maximum of 6 incorrect guesses
* 🔁 Prevents duplicate guesses
* ✅ Input validation
* 📊 Tracks incorrect guesses
* 🏆 Displays a congratulatory message when the word is guessed
* ❌ Displays the correct word when the player loses

## 🛠️ Technologies Used

* **Python 3**
* **Random Module**
* Command-Line Interface (CLI)

## 📚 Python Concepts Used

This project helped me practice the following Python concepts:

* Variables
* Lists
* Strings
* `random.choice()`
* `while` loops
* `for` loops
* `if-else` conditions
* `input()` function
* String manipulation
* Basic input validation

## ▶️ How to Run the Project

### Step 1: Install Python

Make sure Python 3 is installed on your system.

Check your Python installation using:

```bash
python --version
```

### Step 2: Clone the Repository

```bash
git clone https://github.com/your-username/hangman-python.git
```

### Step 3: Navigate to the Project Folder

```bash
cd hangman-python
```

### Step 4: Run the Program

```bash
python hangman.py
```

No external Python packages are required to run this project.

## 🎮 How to Play

1. Start the program.
2. The computer randomly selects a word.
3. The selected word is shown as underscores.
4. Enter one letter at a time.
5. If the letter is correct, it appears in the word.
6. If the letter is incorrect, your incorrect guess count increases.
7. You can make up to **6 incorrect guesses**.
8. Guess the complete word to win the game.

## 💻 Sample Output

```text
Welcome to Hangman!
Guess the word one letter at a time.

Word: _ _ _ _ _ _
Incorrect guesses: 0 / 6

Guess a letter: p
Good guess!

Word: p _ _ _ _ _
Incorrect guesses: 0 / 6

Guess a letter: z
Wrong guess!

Word: p _ _ _ _ _
Incorrect guesses: 1 / 6
```

## 📂 Project Structure

```text
hangman-python/
│
├── hangman.py
└── README.md
```

## 🚀 Future Improvements

The game can be improved further by adding:

* Different difficulty levels
* A larger word database
* A scoring system
* A graphical user interface (GUI)
* Hangman drawing/visuals
* Multiple rounds
* A high-score system

## 🎓 Internship Information

**Internship:** CodeAlpha Internship
**Project:** Python Development
**Project Type:** Console-Based Python Application
**Task:** Hangman Game

This project was completed as part of my **CodeAlpha Internship** to apply Python programming concepts in a practical project.

## 👨‍💻 Author

**Akash**

---

⭐ *This project was created as part of my CodeAlpha Internship to strengthen my Python programming and problem-solving skills.*

