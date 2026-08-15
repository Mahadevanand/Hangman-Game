# 🎮 Hangman Game

A simple **Hangman Game built with Python**.

The computer randomly selects a word, and the player must guess the word one letter at a time. The player has **6 lives** to guess the word correctly.

## 🚀 Features

* 🎲 Randomly selects a word
* 🔤 Allows the player to guess letters
* ❤️ Gives the player 6 lives
* ❌ Loses a life when an incorrect letter is guessed
* 🏆 Displays "You Win!" when the word is completed
* 💀 Displays "You Lose!" when all lives are lost

## 🛠️ Technologies Used

* Python 3
* `random` module
* Lists
* Loops
* Conditional statements
* Functions/variables
* User input

## 📋 Available Words

The current game randomly chooses from:

```text
apple
beautiful
potato
google
microsoft
amazon
```

## ▶️ How to Run

Make sure Python 3 is installed.

Run the following command:

```bash
python hangman.py
```

## 🎮 How to Play

1. Run the program.
2. The computer selects a random word.
3. Enter one letter when asked.
4. If the letter is correct, it appears in the word.
5. If the letter is incorrect, you lose one life.
6. You have 6 lives.
7. Guess all letters before your lives reach zero to win.

## 💻 Example

```text
['_', '_', '_', '_', '_']

Guess a letter: a
['a', '_', '_', '_', '_']

Guess a letter: p
['a', 'p', 'p', '_', '_']

Guess a letter: l
['a', 'p', 'p', 'l', '_']

Guess a letter: e
['a', 'p', 'p', 'l', 'e']

You Win!
```

## 📁 Project Structure

```text
hangman-game/
│
├── hangman.py
├── README.md
├── LICENSE
└── .gitignore
```

## 🔮 Future Improvements

Some improvements that can be added later:

* Add Hangman graphics using ASCII art
* Prevent the player from guessing the same letter repeatedly
* Display remaining lives
* Add more words
* Add difficulty levels
* Add a score system
* Hide the selected word from the player
* Add categories such as animals, countries, fruits, and technology

## 👨‍💻 Author

Sireesha

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
