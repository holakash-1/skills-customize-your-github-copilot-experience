
# 📘 Assignment: Hangman Game Challenge

## 🎯 Objective

Build the classic Hangman word‑guessing game to practice Python strings, loops, conditionals, and random selection.

## 📝 Tasks

### 🛠️ Hangman Game Implementation

#### Description
Write a program that selects a random word from a list and lets the player guess letters until they either discover the word or run out of attempts.

#### Requirements
Completed program should:

- Maintain a predefined list of words and choose one at random when the game starts.
- Prompt the player to guess a single letter using `input()` each turn.
- Display the current progress with underscores for unguessed letters (e.g. `_ a _ g _ a _`).
- Track and display the number of remaining incorrect guesses (start with a fixed number such as 6).
- Prevent repeated guesses from deducting additional attempts.
- End with a clear win message when the word is fully revealed or a lose message when attempts reach zero.

#### Example interaction
```
Word: _ _ _ _ _
Guess a letter: a
Good guess! _ a _ _ _
Guess a letter: e
Sorry, 'e' is not in the word. Attempts remaining: 5
...
```

Feel free to extend the word list or add extra features once the basic requirements are met.
